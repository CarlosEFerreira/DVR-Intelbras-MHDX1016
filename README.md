Monitoramento DVR Intelbras MHDX 1016

<p>O template foi baseado em : https://github.com/GeorgeHPD/Monitoramento-DVR-Intelbras-Zabbix</p>
<p>A dashboard foi baseada em : https://grafana.com/grafana/dashboards/10689</p>
<p>Testado na versão 4.4 Zabbix e 6.5.1 Grafana</p>
<p>1º Edite o grupo "DVR", para o nome do seu grupo no template xml</p>
<p>2º Edite o host "DVR Nome", para o nome do seu host no template xml</p>
<p>3º Edite o SNMP no template de acordo com o snmp ativo no DVR (Template atual está usando v2)</p>
<p>4º Importe o template em HOST no Zabbix</p>
<p>5º Verifique a comunicação do SNMP e a coleta dos itens</p>
<p>6º Se estiver comunicando e coletando, importe o arquivo da Dashboard no Grafana</p>
<p>7º Edite os campos </p>
![config_dashboard](https://user-images.githubusercontent.com/42806550/72466164-1d662e00-37b7-11ea-88b1-829778a2df0d.png)
