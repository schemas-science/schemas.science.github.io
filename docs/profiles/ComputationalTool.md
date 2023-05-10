# ComputationalTool profile

## Description
The Life Science Tools specification provides a way to describe bioscience tools and software on the World Wide Web. It defines a set of metadata and vocabularies, built on top of existing technologies and standards, that can be used to represent such tools in Web pages and applications. The goal of the specification is to make it easier to discover. Version 1.0-RELEASE.<h3>Summary of Changes</h3> <p>Changes since the 0.6-DRAFT</p> <ul> <li>additionalType property deprecated and replaced by applicationCategory.</li><li>example added for the name property.</li></ul>

## Minimum properties

| Name              | Description                          | Cardinality |
| :---------------- | :----------------------------------- | :---------- |
| [description](https://schema.org/description) | A short description of the tool.  | one |
| [name](https://schema.org/name) | The name of the item.  | one |
| [url](https://schema.org/url) | Homepage of the tool. URL of the item.  | one |
| [conformsTo](None) | This is used to state the Bioschemas profile that the markup relates to. The identifier can be the url for the version of this bioschemas class on github: https://github.com/BioSchemas/specifications/blob/master/ComputationalTool/jsonld/ComputationalTool_v1.0-RELEASE.json  | one |


## Recommended properties

| Name              | Description                          | Cardinality |
| :---------------- | :----------------------------------- | :---------- |
| [applicationSubCategory](https://schema.org/applicationSubCategory) | Subcategory of the application, e.g. 'Arcade Game'. Use an EDAM:Topic to describe the category of application  | many |
| [applicationCategory](https://schema.org/applicationCategory) | Type of software application, e.g. 'Game, Multimedia'. Please use terms from the 'Tool type' table in the biotools documentation.  | many |
| [softwareVersion](https://schema.org/softwareVersion) | Version(s) of the tool, which this information is valid for. Can also be a comma-delimited list and include hyphen-separated ranges of versions.  | many |
| [featureList](https://schema.org/featureList) | Features or modules provided by this application (and possibly required by other applications). Functionality provided by the tool. Note: Bioschemas have removed Text from the Expected Types.  | many |
| [author](https://schema.org/author) | The author of this content or rating. Please note that author is special in that HTML 5 provides a special mechanism for indicating authorship via the rel tag. That is equivalent to this and may be used interchangeably.  | many |
| [citation](https://schema.org/citation) | Publication about this tool. A citation or reference to another creative work, such as another publication, web page, scholarly article, etc.  | many |
| [license](https://schema.org/license) | The license of a software, curated dataset, etc. A license document that applies to this content, typically indicated by URL. Use SPDX list of licenses in form https://spdx.org/licenses/  | many |


## Optional properties
| Name              | Description                          | Cardinality |
| :---------------- | :----------------------------------- | :---------- |
| [codeRepository](https://schema.org/codeRepository) | Link to the source code repository of the tool.  | many |
| [input](https://schema.org/input) | Specification of a consumed input.  | many |
| [output](https://schema.org/output) | Specification of a produced output.  | many |
| [programmingLanguage](https://schema.org/programmingLanguage) | The main programming language(s) used to build or execute the tool. Please use terms from the ‘Programming language’ table in the Bio.Tools documentation  | many |
| [downloadUrl](https://schema.org/downloadUrl) | Link(s) to the downloadable(s).  | many |
| [applicationSuite](https://schema.org/applicationSuite) | A suite of tools, to which the tool belongs. The name of the application suite to which the application belongs (e.g. Excel belongs to Office).  | many |
| [softwareHelp](https://schema.org/softwareHelp) | A documentation of the tool.  | many |
| [softwareAddOn](https://schema.org/softwareAddOn) | Additional sub-tools (add-ons, plug-ins, tools in a suite, etc.) that are included in the tool or workflow. Additional content for a software application.  | many |
| [operatingSystem](https://schema.org/operatingSystem) | Operating systems on which the tool can be used (without additional wrapping). Operating systems supported (Windows 7, OSX 10.6, Android 1.6). Please use terms from the ‘Operating systems’ table in the biotools documentation  | many |
| [identifier](https://schema.org/identifier) | The identifier property represents any kind of identifier for any kind of <a class="localLink" href="http://schema.org/Thing">Thing</a>, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See <a href="/docs/datamodel.html#identifierBg">background notes</a> for more details.  | many |
| [contributor](https://schema.org/contributor) | A secondary contributor to the CreativeWork or Event.  | many |
| [discussionUrl](https://schema.org/discussionUrl) | A link to the page containing the comments of the CreativeWork.  | many |
| [funder](https://schema.org/funder) | A person or organization that supports (sponsors) something through some kind of financial contribution.  | many |
| [hasPart](https://schema.org/hasPart) | Indicates any software dependency. Indicates an item or CreativeWork that is part of this item, or CreativeWork (in some sense).  | many |
| [isAccessibleForFree](https://schema.org/isAccessibleForFree) | A flag to signal that the tool or the service are available to be used for free.  | one |
| [isBasedOn](https://schema.org/isBasedOn) | A tool or another work which this tool is based on, or is an extension, distribution, or deployment of.  A resource from which this work is derived or from which it is a modification or adaption.  | many |
| [isPartOf](https://schema.org/isPartOf) | A collection, other than a suite of tools, to which the tool belongs.. Indicates an item or CreativeWork that this item, or CreativeWork (in some sense), is part of.  | many |
| [keywords](https://schema.org/keywords) | Additional keywords or tags important for this tool. Multiple entries are delimited by commas. Keywords or tags used to describe this content. Multiple entries in a keywords list are typically delimited by commas.  | many |
| [provider](https://schema.org/provider) | The provider organization of a web application, database portal, web service, etc. Note: Bioschemas have removed Person from the Expected Types. The service provider, service operator, or service performer; the goods producer. Another party (a seller) may offer those services or goods on behalf of the provider. A provider may also serve as the seller.  | many |
| [thumbnailUrl](https://schema.org/thumbnailUrl) | A small image representing the tool, such as an icon. A thumbnail image relevant to the Thing.  | one |
