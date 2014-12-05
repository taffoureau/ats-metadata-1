
# Keyword for datasets

# Test case identifier	

md_IR223_2

# Test purpose	

If the resource is a dataset or a dataset series, at least one keyword must originate from the INSPIRE theme of the GEMET Thesaurus

# Test method	

Checks for every gmd:keyword found at gmd:identificationInfo[1]/*/gmd:descriptiveKeywords/*/ 
if it is formatted as either gco:CharacterString or gmd:PT_FreeText. In the latter case, a schema validation is 
performed depending on the GML version (see About schema validation). It the checks for every keyword if its text content 
can be found in either the indicated language or english version 
 of the INSPIRE GEMET Thesaurus ( http://inspire.ec.europa.eu/theme ). If at least one keyword from that source is found, the test succeeds, otherwise it will fail.
If the type of the resource is not dataset or series, this test is omitted.



# Reference	 

IR Chap. 2.2.3
INSPIRE themes at http://inspire.ec.europa.eu/theme
TG Req 14

# Test type	

Automated

