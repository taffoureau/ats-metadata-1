
# Resolution

**Purpose**	

If the type of the resource was dataset or series, Each [spatial resolution](#spatialResolution) is either an [equivalentScale](#equivalentScale) OR a ground
sample [distance](#distance). 

**Test method**	

Each spatialResolution element must contain either an equivalent scale or a distance but not both

**Reference(s)**	 

TG, Req 27

**Test type:** Automated

**Notes**

**Contextual XPath references**

The namespace prefixes used as described in [README.md](./README.md#namespaces).

Abbreviation                                   |  XPath expression (relative to gmd:MD_Metadata)
-----------------------------------------------| -------------------------------------------------------------------------
<a name="spatialResolution"></a> spatialResolution | ./gmd:identificationInfo/*/gmd:MD_DataIdentification/*/gmd:spatialResolution
<a name="equivalentScale"></a> equivalentScale  | ./gmd:spatialResolution/gmd:MD_Resolution/gmd:equivalentScale
<a name="distance"></a> distance   | ./gmd:spatialResolution/gmd:MD_Resolution/gmd:distance/gco:Distance



