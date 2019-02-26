# zabbix-cachet-k8s-cronjob

# ENVIRONMENT variables to set

* ZABBIXAPI - zabbix api url
* ZAPIUSER - zabbix api user
* ZAPIPASS - zabbi api password
* ITEMID - zabbix item id
* ITEMTYPE - item type, required for API requests to history
<br>0 - numeric float; 
<br>1 - character; 
<br>2 - log; 
<br>3 - numeric unsigned; 
<br>4 - text. 
* VALUESCOUNT - zabbix values to get from history
* METRICID - cachet metricid
* CACHETAPI - cachet api url
* CACHET_TOKEN - cachet access token
