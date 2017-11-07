<strong>Open Refine Resources</strong>

Data Sets:
1. http://chroniclingamerica.loc.gov/search/titles/results/?terms=michigan&format=json
2. report data taken from https://tomcat.wrlc.org/rpt/retmissing_form.html
3. https://auislandora.wrlc.org/oai2?verb=ListRecords&set=auhist_876&metadataPrefix=oai_dc

GREL Code Snippets
1. To run a simple true/false test based on cell contents - value.endsWith("your_string") or value.startsWith("your_string") as in value.endsWith("perm")
2. To replace all instances of value #1 with value #2 to something else - value.replace("value1","value2") as in value.replace("Michigan","The Best State Ever")
3. More GREL Tips in the "GRELtips.txt" file

Templating
Aaron's DC to MODS OpenRefine Template
https://gist.github.com/krebeck/1c3c0257cecb25eb1a7c


