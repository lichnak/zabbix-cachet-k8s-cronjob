This is a kubernetes cronjob with pushes one zabbix (history) metric to a cachet metric.

# ENVIRONMENT variables to set

* ZABBIXAPI - zabbix api url {https://zabbix.domain/zabbix//api_jsonrpc.php}
* ZAPIUSER - zabbix api user
* ZAPIPASS - zabbi api password
* ITEMID - zabbix item id
* ITEMTYPE - item type, required for API requests to history
* CACHETAPI - your cachethq url {https://cachethq.domain/api/v1/}, pay attention on trailing slash
* CACHET_TOKEN - your cachethq user token
<br>0 - numeric float; 
<br>1 - character; 
<br>2 - log; 
<br>3 - numeric unsigned; 
<br>4 - text. 
* VALUESCOUNT - zabbix values to get from history
* METRICID - cachet metricid
* CACHETAPI - cachet api url
* CACHET_TOKEN - cachet access token
