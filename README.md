# AppClientServerJava
Aplicação Java para troca de arquivos entre cliente-servidor

Pré-requisitos:
- Conexão com banco de dados MongoDB;

Execução:
- Executar app do Servidor, em seguida executar app do cliente;

Funcionamento:
- O ClienteEx cria e preenche um arquivo, armazena localmente, converte em um array de bytes e envia ao servidor;
- O ServidorEx recebe o array de bytes converte no arquivo enviado pelo cliente, armazena localmente e salva seu conteúdo no banco de dados; 
