# gerenciamento-estoque-clientes-servico

Este é um sistema de controle de estoque com código de barras (cadastro, entrada, saída, relatório), cadastro de clientes e de serviços realizados, que desenvolvi em 2019, durante o 1º ano da faculdade, voltado para uma empresa de produtos ortopédicos. Atualmente a empresa ainda utiliza o sistema em seu dia-a-dia.

Desenvolvido em Java (pojo/DAO), Firebird e relatórios JasperReports.

Para ativar a saída de relatório, é necessário fazer o download do iReport, para alterar a string de conexão com o banco no arquivo .jrxml, que gera o arquivo .jasper que o sistema irá utilizar.

Estão inclusos os arquivos do banco de dados firebird (.FDB) e o script usado para criar o banco (Script bd.txt).
É necessário instalar o FireBird para rodar o banco de dados. 

Para garantir o funcionamento, importe todas as bibliotecas na pasta lib para dentro do projeto.

Sinta-se livre para utilizar o código, e, se puder, dar uma estrela no GitHub!
