# Open Refine Resources

<strong>Data Sets:</strong>
1. http://chroniclingamerica.loc.gov/search/titles/results/?terms=michigan&format=json
2. a.  report data taken from https://tomcat.wrlc.org/rpt/retmissing_form.html (Voyager)
2. b.  report data taken from Alma Analytics Tool https://analytics-na02.alma.exlibrisgroup.com/analytics/saw.dll?Go
https://wrlc-network.alma.exlibrisgroup.com/infra/report?path=Go@Options=fdr@path=/shared/Alma/Physical%20Item%20Usage%20for%20Weeding/Reports/&reportName=3.%20Items%20in%20library%20at%20least%20five%20years%20and%20never%20loaned%20in%20last%20five%20years%20with%20prompt%20for%20library%20name&Action=Prompt
3. https://auislandora.wrlc.org/oai2?verb=ListRecords&set=auislandora_8322&metadataPrefix=oai_dc


<strong>GREL Code Snippets</strong>
1. To run a simple true/false test based on cell contents - value.endsWith("your_string") or value.startsWith("your_string") as in value.endsWith("perm")
2. To replace all instances of value #1 with value #2 to something else - value.replace("value1","value2") as in value.replace("Michigan","The Best State Ever")
3. More GREL Tips in the "GRELtips.txt" file

<strong>Templating</strong><br>
Aaron's DC to MODS OpenRefine Template
https://gist.github.com/krebeck/1c3c0257cecb25eb1a7c
