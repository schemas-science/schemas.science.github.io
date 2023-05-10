# Dataset profile

## Description
A guide for how to describe datasets in the life-sciences using Schema.org-like annotation. Version 1.0-RELEASE. <h3>Summary of Changes</h3> <br>Key changes since 0.3-RELEASE:<ul><li>Updated properties to Schema.org v12.0; various properties added at recommended or optional level, expected types updated. See 0.4-DRAFT for full details</li><li>license now a minimum property</li><li>keywords: Cardinality #501 – Cardinality is MANY</li><li>distribution: Cardinality #574 – Cardinality changed to MANY</li><li>datePublished: Increased marginlity #576 – Now recommended</li><li>publisher: Increased marginlity, Cardinality #576 – Now recommended with MANY cardinality</li></ul>

## Minimum properties

| Name              | Description                          |
| :---------------- | :----------------------------------- |
| description | A short summary describing a dataset. A description of the item.  |
| identifier | CURIEs that can be resolved using [Identifiers.org](https://identifiers.org/) should be used. The identifier property represents any kind of identifier for any kind of [Thing](https://schema.org/Thing), such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See [background notes](http://schema.org/docs/datamodel.html#identifierBg) for more details.  |
| keywords | Keywords should be drawn from a controlled vocabulary, e.g. [EDAM](https://edamontology.org/), and supplied as a DefinedTerm list. Keywords or tags used to describe this content. Multiple entries in a keywords list are typically delimited by commas.  |
| license | A license under which the dataset is distributed. A license document that applies to this content, typically indicated by URL.  |
| name | A descriptive name of the dataset. The name of the item.  |
| url | The location of a page describing the dataset. URL of the item.  |
| conformsTo | This is used to state the Bioschemas profile that the markup relates to. The identifier can be the url for the version of this bioschemas class on github: https://github.com/BioSchemas/specifications/blob/master/Dataset/jsonld/Dataset_v1.0-RELEASE.json  |


## Recommended properties

| Name              | Description                          |
| :---------------- | :----------------------------------- |
| alternateName |  An alias for the item.  |
| citation | A citation for a publication that describes the dataset. A citation or reference to another creative work, such as another publication, web page, scholarly article, etc.  |
| creator | The name of the dataset creator (person or organization). The creator/author of this CreativeWork. This is the same as the Author property for CreativeWork.  |
| datePublished |  Date of first broadcast/publication.  |
| distribution |  A downloadable form of this dataset, at a specific location, in a specific format.  |
| includedInDataCatalog |  A data catalog which contains this dataset. Supersedes [includedDataCatalog](https://schema.org/includedDataCatalog), [catalog](https://schema.org/catalog).
Inverse property: [dataset](https://schema.org/dataset)  |
| isBasedOn | Use to link a Dataset to the Study that it was generated from. A resource that was used in the creation of this resource. This term can be repeated for multiple sources. For example, http://example.com/great-multiplication-intro.html. 
Supersedes isBasedOnUrl.  |
| measurementTechnique |  A technique or technology used in a [Dataset](https://schema.org/Dataset) (or [DataDownload](https://schema.org/DataDownload), [DataCatalog](https://schema.org/DataCatalog)), corresponding to the method used for measuring the corresponding variable(s) (described using [variableMeasured](https://schema.org/variableMeasured)). This is oriented towards scientific and scholarly dataset publication but may have broader applicability; it is not intended as a full representation of measurement, but rather as a high level summary for dataset discovery.

For example, if [variableMeasured](https://schema.org/variableMeasured) is: molecule concentration, [measurementTechnique](https://schema.org/measurementTechnique) could be: "mass spectrometry" or "nmr spectroscopy" or "colorimetry" or "immunofluorescence".

If the [variableMeasured](https://schema.org/variableMeasured) is "depression rating", the [measurementTechnique](https://schema.org/measurementTechnique) could be "Zung Scale" or "HAM-D" or "Beck Depression Inventory".

If there are several [variableMeasured](https://schema.org/variableMeasured) properties recorded for some given data object, use a [PropertyValue](https://schema.org/PropertyValue) for each [variableMeasured](https://schema.org/variableMeasured) and attach the corresponding [measurementTechnique](https://schema.org/measurementTechnique).  |
| variableMeasured | What does the dataset measure? (e.g., temperature, pressure). The variableMeasured property can indicate (repeated as necessary) the variables that are measured in some dataset, either described as text or as pairs of identifier and description using PropertyValue.  |
| version | The version number for this dataset. The version of the CreativeWork embodied by a specified resource.  |


## Optional properties
| Name              | Description                          |
| :---------------- | :----------------------------------- |
| dateCreated |  The date on which the CreativeWork was created or the item was added to a DataFeed.  |
| dateModified |  The date on which the CreativeWork was most recently modified or when the item's entry was modified within a DataFeed.  |
| hasPart |  Indicates an item or CreativeWork that is part of this item, or CreativeWork (in some sense). 
Inverse property: [isPartOf](https://schema.org/isPartOf)  |
| isAccessibleForFree |  A flag to signal that the item, event, or place is accessible for free. Supersedes [free](https://schema.org/free).  |
| isPartOf |  Indicates an item or CreativeWork that this item, or CreativeWork (in some sense), is part of. Inverse property: [hasPart](https://schema.org/hasPart)  |
| maintainer |  A maintainer of a [Dataset](https://schema.org/Dataset), software package ([SoftwareApplication](https://schema.org/SoftwareApplication)), or other [Project](https://schema.org/Project). A maintainer is a [Person](https://schema.org/Person) or [Organization](https://schema.org/Organization) that manages contributions to, and/or publication of, some (typically complex) artifact. It is common for distributions of software and data to be based on "upstream" sources. When [maintainer](https://schema.org/maintainer) is applied to a specific version of something e.g. a particular version or packaging of a [Dataset](https://schema.org/Dataset), it is always possible that the upstream source has a different maintainer. The [isBasedOn](https://schema.org/isBasedOn) property can be used to indicate such relationships between datasets to make the different maintenance roles clear. Similarly in the case of software, a package may have dedicated maintainers working on integration into software distributions such as Ubuntu, as well as upstream maintainers of the underlying work.  |
| publisher |  The publisher of the creative work.  |
| sameAs |  URL of a reference Web page that unambiguously indicates the item's identity. E.g. the URL of the item's Wikipedia page, Wikidata entry, or official website.  |
