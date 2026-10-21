TP01 - Integração de Sistemas de Informação
Autores
a29369 - Simão Martinho Vidal

a29370 - Rúben Salgado

Link do Vídeo de Demonstração
https://drive.google.com/file/d/1G8mCgfqIIa0vhR3KEYZ0Rk0zt4WIzOG_/view?usp=drive_link

Descrição dos Ficheiros
/doc: Contém o relatório final do trabalho prático em formato PDF.

/dataintegration: Contém a transformação do Pentaho Kettle (.ktr) e o workflow do KNIME.

/data/input: Contém os dados de origem (Jogadores.csv e Partidas.json).

/data/output: Contém os exemplos de dados persistidos após o ETL (.csv, .json, .xml).

/src: Contém o código fonte do Node-RED (flows.json).

Como Executar a Solução
Node-RED: Importar o ficheiro flows.json (Menu > Import) e clicar em Deploy.

Kettle / KNIME: Abrir as respetivas transformações. Garantir que os caminhos dos nós de leitura (CSV file input e JSON input) apontam para a pasta /data/input local do computador onde o projeto for testado.

Executar o fluxo no Kettle/KNIME para iniciar o processamento e o envio dos dados via HTTP POST.

Abrir o Node-RED Dashboard em http://127.0.0.1:1880/ui para ver a visualização.