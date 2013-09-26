Solr-i käivitamine:
	pakkida lahti kaust "MyReader solr"
	navigeerida konsoolis kausta: ...\solr-4.3.1\example
	käivitada käsklusega: java -jar start.jar
	
	Solr-i pordi muutmine:
		...\solr-4.3.1\example\etc\jetty.xml
		rida 56: <Set name="port"><SystemProperty name="jetty.port" default="9090"/></Set>
	(Solr-i kaustas leidub teisigi faile, kus määratakse porti, kuid andmed leitakse ka neid muutmata ja 
	ma ei tea kas nad mängivad rolli:
	...\solr-4.3.1\example\conf\dataimport.properties - rida 22
	...\solr-4.3.1\example\solr\solr.xml - rida 50 )