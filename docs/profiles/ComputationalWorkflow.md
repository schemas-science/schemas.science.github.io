# ComputationalWorkflow profile

## Description
A computational workflow consists of an orchestrated and repeatable pattern of activity enabled by the systematic organization of resources into processes that transform materials, provide services, or process information (source Wikipedia.org). It is executed by a computational process and is thus distinct from laboratory or business workflows. version 1.0-RELEASE

## Minimum properties

| Name              | Description                          | Cardinality |
| :---------------- | :----------------------------------- | :---------- |
| [input](https://schema.org/input) | An input required to use the computational workflow (eg. Excel spreadsheet, BAM file)  | many |
| [output](https://schema.org/output) | An output produced by the workflow  | many |
| [programmingLanguage](https://schema.org/programmingLanguage) | The computer programming language.  | many |
| [name](https://schema.org/name) | The name of the item.  | one |
| [url](https://schema.org/url) | URL of the item.  | one |
| [creator](https://schema.org/creator) | The creator/author of this CreativeWork. This is the same as the Author property for CreativeWork.  | many |
| [dateCreated](https://schema.org/dateCreated) | The date on which the CreativeWork was created or the item was added to a DataFeed.  | one |
| [license](https://schema.org/license) | A license document that applies to this content, typically indicated by URL.  | many |
| [sdPublisher](https://schema.org/sdPublisher) | Indicates the party responsible for generating and publishing the current structured data markup, typically in cases where the structured data is derived automatically from existing published content but published on a different site. For example, student projects and open data initiatives often re-publish existing content with more explicitly structured metadata. The <a class="localLink" href="http://schema.org/sdPublisher">sdPublisher</a> property helps make such practices more explicit.  | many |
| [version](https://schema.org/version) | The version of the CreativeWork embodied by a specified resource.  | one |
| [conformsTo](None) | This is used to state the Bioschemas profile that the markup relates to. The identifier can be the url for the version of this bioschemas class on github: https://github.com/BioSchemas/specifications/blob/master/ComputationalWorkflow/jsonld/ComputationalWorkflow_v1.0-RELEASE.json  | one |


## Recommended properties

| Name              | Description                          | Cardinality |
| :---------------- | :----------------------------------- | :---------- |
| [creativeWorkStatus](https://schema.org/creativeWorkStatus) | The status of a creative work in terms of its stage in a lifecycle. Example terms include Incomplete, Draft, Published, Obsolete. Some organizations define a set of terms for the stages of their publication lifecycle.  | many |
| [documentation](https://schema.org/documentation) | Documentation describing the ComputationalWorkflow and its use.  | many |
| [funding](https://schema.org/funding) | The funding for the workflow  | many |
| [maintainer](https://schema.org/maintainer) |  maintainer of a Dataset, software package (SoftwareApplication), or other Project. A maintainer is a Person or Organization that manages contributions to, and/or publication of, some (typically complex) artifact. It is common for distributions of software and data to be based on “upstream” sources. When maintainer is applied to a specific version of something e.g. a particular version or packaging of a Dataset, it is always possible that the upstream source has a different maintainer. The isBasedOn property can be used to indicate such relationships between datasets to make the different maintenance roles clear. Similarly in the case of software, a package may have dedicated maintainers working on integration into software distributions such as Ubuntu, as well as upstream maintainers of the underlying work.  | many |
| [softwareRequirements](https://schema.org/softwareRequirements) | Renaming schema.org/requirements as softwareRequirements. Component dependency requirements for application. This includes runtime environments and shared libraries that are not included in the application distribution package, but required to run the application (Examples: DirectX, Java or .NET runtime). Supersedes requirements.   | many |
| [targetProduct](https://schema.org/targetProduct) | Target Operating System / Product to which the code applies.  If applies to several versions, just the product name can be used.  | many |
| [runtimePlatform](https://schema.org/runtimePlatform) | Runtime platform or script interpreter dependencies (Example - Java v1, Python2.3, .Net Framework 3.0).  | many |
| [description](https://schema.org/description) | A description of the item.  | one |
| [citation](https://schema.org/citation) | A citation or reference to another creative work, such as another publication, web page, scholarly article, etc.  | many |
| [contributor](https://schema.org/contributor) | A secondary contributor to the CreativeWork or Event.  | many |
| [hasPart](https://schema.org/hasPart) | Indicates an item or CreativeWork that is part of this item, or CreativeWork (in some sense).  | many |
| [isBasedOn](https://schema.org/isBasedOn) | A resource from which this work is derived or from which it is a modification or adaption.  | one |
| [keywords](https://schema.org/keywords) | Keywords or tags used to describe this content. Multiple entries in a keywords list are typically delimited by commas.  | many |
| [producer](https://schema.org/producer) | The person or organization who produced the work (e.g. music album, movie, tv/radio series etc.).  | many |
| [publisher](https://schema.org/publisher) | The publisher of the creative work.  | many |


## Optional properties
| Name              | Description                          | Cardinality |
| :---------------- | :----------------------------------- | :---------- |
| [conditionsOfAccess](https://schema.org/conditionsOfAccess) | Conditions that affect the availability of, or method(s) of access to, an item. Typically used for real world items such as an ArchiveComponent held by an ArchiveOrganization. This property is not suitable for use as a general Web access control mechanism. It is expressed only in natural language.  For example “Available by appointment from the Reading Room” or “Accessible only from logged-in accounts “.  | one |
| [alternateName](https://schema.org/alternateName) | An alias for the item.  | many |
| [identifier](https://schema.org/identifier) | The identifier property represents any kind of identifier for any kind of <a class="localLink" href="http://schema.org/Thing">Thing</a>, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See <a href="/docs/datamodel.html#identifierBg">background notes</a> for more details.  | many |
| [image](https://schema.org/image) | An image of the item. This can be a <a class="localLink" href="http://schema.org/URL">URL</a> or a fully described <a class="localLink" href="http://schema.org/ImageObject">ImageObject</a>.  | many |
| [dateModified](https://schema.org/dateModified) | The date on which the CreativeWork was most recently modified or when the item's entry was modified within a DataFeed.  | one |
| [datePublished](https://schema.org/datePublished) | Date of first broadcast/publication.  | one |
| [encodingFormat](https://schema.org/encodingFormat) | Media type typically expressed using a MIME format (see <a href="http://www.iana.org/assignments/media-types/media-types.xhtml">IANA site</a> and <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types">MDN reference</a>) e.g. application/zip for a SoftwareApplication binary, audio/mpeg for .mp3 etc.).<br/><br/>  In cases where a <a class="localLink" href="http://schema.org/CreativeWork">CreativeWork</a> has several media type representations, <a class="localLink" href="http://schema.org/encoding">encoding</a> can be used to indicate each <a class="localLink" href="http://schema.org/MediaObject">MediaObject</a> alongside particular <a class="localLink" href="http://schema.org/encodingFormat">encodingFormat</a> information.<br/><br/>  Unregistered or niche encoding and file formats can be indicated instead via the most appropriate URL, e.g. defining Web page or a Wikipedia/Wikidata entry.  | many |
