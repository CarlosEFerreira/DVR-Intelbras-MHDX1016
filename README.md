Monitoramento DVR Intelbras MHDX 1016

O template foi baseado em : https://github.com/GeorgeHPD/Monitoramento-DVR-Intelbras-Zabbix
A dashboard foi baseada em : https://grafana.com/grafana/dashboards/10689

Testado na versão 4.4 Zabbix e 6.5.1 Grafana

1º Edite o grupo "DVR", para o nome do seu grupo no template xml
2º Edite o host "DVR Nome", para o nome do seu host no template xml
3º Edite o SNMP no template de acordo com o snmp ativo no DVR (Template atual está usando v2)
4º Importe o template em HOST no Zabbix
5º Verifique a comunicação do SNMP e a coleta dos itens
6º Se estiver comunicando e coletando, importe o arquivo da Dashboard no Grafana
7º Edite os campos 
