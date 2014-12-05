
# Conditions applying to access and use

# Test case identifier	

md_292

# Test purpose	

Conditions applying to access and use must be described at least once for the resource.

# Test method	

The test checks if an element is given at $response//gmd:identificationInfo[1]/*/gmd:resourceConstraints/*/gmd:useLimitation.

If no conditions apply to the access and use of the resource, �no
conditions apply� shall be used. If conditions are unknown, �conditions
unknown� shall be used.

Descriptions of terms and conditions, including where applicable, the
corresponding fees shall be provided through this element or a link
(URL) where these terms and conditions are described.

# Reference	 

INSPIRE Metadata Implementing Rules, Chap. 2.9.2 
TG Req 33,34

# Test type	

Automated
