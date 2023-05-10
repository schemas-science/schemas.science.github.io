# Title

## Introduction 

bla bla bla 

## Content 


| Name              | Description                          |
| :---------------- | :----------------------------------- |
| ChemicalSubstance | This profile describes a ChemicalSubstance which is 'a portion of matter of constant composition, composed of molecular entities of the same type or of different types' (source: ChEBI:59999). Note, the parent class for this profile has been updated to a pending class in schema.org.  |
| Gene | Bioschemas profile describing a Gene in Life Sciences. This Gene profile specification presents the markup for describing a Gene and is based on the 1.0 release. Note, the parent class for this profile has been updated to a pending class in schema.org.  |
| Taxon | Bioschemas profile for describing a biological taxon This profile aims to denote a taxon by common properties such as its scientific name, taxonomic rank and vernacular names. It is also a means to link to existing taxonomic registers where each taxon has a URI. Version 1.0-RELEASE.<br/><h3>Summary of Changes</h3><br>Changes since 0.8-DRAFT:<ul><li>None. Version 0.8-DRAFT was the draft approved for release.</li></ul>  |
| MolecularEntity | Bioschemas profile describing a MolecularEntity. Any constitutionally or isotopically distinct atom, molecule, ion, ion pair, radical, radical ion, complex, conformer etc., identifiable as a separately distinguishable entity. (Source: ChEBI:23367) based on version 0.5. Note, the parent class for this profile has been updated to a pending class in schema.org.  |
| Protein | Bioschemas profile describing a Protein in Life Sciences. This Protein profile specification presents the most common properties used for a Protein and is based on Version 0.11. Note, the parent class for this profile has been updated to a pending class in schema.org.  |
| FormalParameter | Bioschemas specification for describing a formal parameter in the Life Sciences. Version: 1.0-RELEASE (09 March 2021)   |
| ComputationalTool | The Life Science Tools specification provides a way to describe bioscience tools and software on the World Wide Web. It defines a set of metadata and vocabularies, built on top of existing technologies and standards, that can be used to represent such tools in Web pages and applications. The goal of the specification is to make it easier to discover. Version 1.0-RELEASE.<h3>Summary of Changes</h3> <p>Changes since the 0.6-DRAFT</p> <ul> <li>additionalType property deprecated and replaced by applicationCategory.</li><li>example added for the name property.</li></ul>  |
| ComputationalWorkflow | A computational workflow consists of an orchestrated and repeatable pattern of activity enabled by the systematic organization of resources into processes that transform materials, provide services, or process information (source Wikipedia.org). It is executed by a computational process and is thus distinct from laboratory or business workflows. version 1.0-RELEASE  |
| DataCatalog | A guide for how to describe data catalogs/repositories in the life-sciences using Schema.org-like annotation. Version 0.3-RELEASE-2019_07_01  |
| Dataset | A guide for how to describe datasets in the life-sciences using Schema.org-like annotation. Version 1.0-RELEASE. <h3>Summary of Changes</h3> <br>Key changes since 0.3-RELEASE:<ul><li>Updated properties to Schema.org v12.0; various properties added at recommended or optional level, expected types updated. See 0.4-DRAFT for full details</li><li>license now a minimum property</li><li>keywords: Cardinality #501 – Cardinality is MANY</li><li>distribution: Cardinality #574 – Cardinality changed to MANY</li><li>datePublished: Increased marginlity #576 – Now recommended</li><li>publisher: Increased marginlity, Cardinality #576 – Now recommended with MANY cardinality</li></ul>  |
| Sample | To deliver on the identified use cases for samples, we have identified a minimal set of properties to encapsulate identification, linking, and metadata descriptions. Some of these properties are existing standard schema.org properties, others require Bioschemas extensions. Table 1 outlines the minimal set of properties for the ‘Sample’ concept and Table 2 shows our recommendations for use of the ‘PropertyValue’ concept to markup additional characteristics of a sample described within a sample page. We also propose a new concept, ‘Biomedical Code’, which is a generalisation of the existing ‘Medical Code’ concept defined in the health-lifesci.schema.org extension.  |
| Course | Specification describing a course.  This specification must be used in tandem with a courseInstance. A course is used to describe the broad, common aspects of a recurring training event - whereas a course instance is about the specific times and location of when that course is held. <h4>Summary of Changes</h4>    No changes since 0.10-DRAFT of the Course profile.</li>         </ul> Version: 1.0-RELEASE (13 September 2022)   |
| CourseInstance | Specification describing the instance of a course.  This specification can be used in tandem with a Course. A course is used to describe the broad, common aspects of a recurring training event - whereas a course instance is about the specific times and location of when that course is held. <h4>Summary of Changes</h4>    No changes since 0.9-DRAFT of the CourseInstance profile. Version: 1.0-RELEASE (13 September 2022)  |
| TrainingMaterial | A specification for describing training materials in life sciences. The Life Science Training Materials specification provides a way to describe bioscience training material on the World Wide Web. It defines a set of metadata and vocabularies, built on top of existing technologies and standards, that can be used to represent events in Web pages and applications. The goal of the specification is to make it easier to discover, exchange and integrate life science training material information across the Internet.<h4>Summary of Changes</h4> No changes since 0.9-DRAFT of the TrainingMaterials profile. Version: 1.0-RELEASE  |
| TaxonName | Bioschemas profile for describing a name of a biological taxon, which may be valid (zoology) / accepted (botany) or not. This profile povides a way to denote the scientific names of a taxon. The taxon accepted/valid name is linked to the taxon with property scientificName while the synonyms are linked with property alternateScientificName. Version: 1.0-RELEASE. <h3>Summary of Changes</h3><br>Changes since Version 0.2-DRAFT:<ul><li>None. Version 0.2-DRAFT was approved to become a release</li></ul>  |
| hasStatus | One of pseudogene, dead, killed, live, predicted, suppressed.  |
| vernacularName | A vernacular (common) name of the taxon.  |
| scientificName | A TaxonName representing the currently valid (zoological) or accepted (botanical) name for that taxon.  |
| alternateScientificName | A TaxonName representing a scientific name, with authorship and date information if known, of a synonym of the currently valid (zoological) or accepted (botanical) name.  |
| isBasedOn | A resource from which this work is derived or from which it is a modification or adaption. Supersedes, isBasedOnUrl. 
 A CreativeWork, such as a scholarly article, asserting the status of the accepted/valid name and synonyms, retained for the taxon circumscription.  |
| codeRepository | Link to the repository where the un-compiled, human readable code and related code is located (SVN, github, CodePlex).  |
| input | Specification of a consumed input.  |
| output | Specification of a produced output.  |
| programmingLanguage | The computer programming language.  |
| conformsTo | Used to state the Bioschemas profile that the markup relates to. The versioned URL of the profile must be used. Note that we use a CURIE in the table here but the full URL for Dublin Core terms must be used in the markup (http://purl.org/dc/terms/conformsTo), see example.  |





