# DCAT2 Null Profile
This is a *profile* of the [Data Catalog Vocabulary (DCAT) - Version 2](https://www.w3.org/TR/vocab-dcat/) implemented by [SURROUND Australia](https://surroundaustralia.com) to allow for the validation of datasets according to DCAT2.

By *profile*, what is meant here is "A specification that constrains, extends, combines, or provides guidance or explanation about the usage of other specifications." (from [PROF](https://www.w3.org/TR/dx-prof/#definitions)) and, here the *other specification* is SKOS.

This profile implements no constraints, extensions or combinations on top of DCAT2 this it is a "null" profile whose only purpose is to provide a machine-readable validator for DCAT2 data.

This profile is formulated according to the [Profiles Vocabulary](https://www.w3.org/TR/dx-prof/) and provides a single [Shapes Constraint Language (SHACL)](https://www.w3.org/TR/shacl/) validator file for automated data validation.

This profile is hosted online in [Linked Data](https://www.w3.org/standards/semanticweb/data) form using a persistent web address:

* <https://w3id.org/profile/dcat2null>


## Profile Resources

### Validator
This profile's rules, as extracted from the DCAT2 specification (the standard) are presented for machine validation of RDF vocabularies in the file [validator.shacl.ttl](validator.shacl.ttl) which conforms to the [SHACL](https://www.w3.org/TR/shacl/) standard.

Tools such as [pySHACL](https://github.com/RDFLib/pySHACL) and the online [SHACL Playground](https://shacl.org/playground/) can be used with this Validator to validate vocabulary files.

### Examples
Some examples of valid and invalid DCAT2 statements are given in the [examples/](examples/) folder.


## License  
This code is licensed using the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) licence. See the [LICENSE file](LICENSE) for the deed. 

Note [Citation](#citation) below for attribution.


## Citation
To cite this profile, please use the following (formulated in [BibTex](http://www.bibtex.org/)):

```
@software{dcat2-null-profile,
  author = {{SURROUND Australia Pty Ltd}},
  title = {{DCAT2 Null Profile}},
  version = {1.0},
  date = {2021},
  publisher = {{SURROUND Australia Pty Ltd}},
  url = {https://w3id.org/profile/dcat2null}
}
``` 


## Contact
*publisher:*  
![](style/SURROUND-logo-100.png)  
**SURROUND Australia Pty. Ltd.**  
<https://surroundaustralia.com>  

*creator:*  
**Dr Nicholas J. Car**  
*Data Systems Architect*  
SURROUND Australia Pty. Ltd.  
<nicholas.car@surroudaustralia.com>  
<https://orcid.org/0000-0002-8742-7730>