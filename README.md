# Recursos do template
Esse template do zabbix monitora as informações do sistema "SCI Único Sistema Contábil"

## Itens monitorados:
No Zabbix é possível monitorar:
- status do banco de dados 
- uptime do banco de dados
- número de conexões ativas com o banco de dados
- número de conexões em standby

## Triggers
Exitem duas triggers:
- Banco de dados não está em execução
- Sem dados recentes do SCI Unico

## Gráficos
O gráfico disponível exibe o número de conexões ativas com o banco de dados.

# Como utilizar
Baixe o arquivo `zabbix-template-sci-unico.yaml`

Edite as menções de `D:\SCI\servidor\infos.xml` e insira o caminho do arquivo em seu servidor.

Faça o upload do Template em seu Zabbix e associe-o no host que roda o "SCI Úníco Sistema Contábil"

# Informação adicional
Testado com o Zabbix na versão 6.0 LTS.

Esse não é um template oficial da empresa que criou o sistema.