# ComputationalTool profile

## Description
The Life Science Tools specification provides a way to describe bioscience tools and software on the World Wide Web. It defines a set of metadata and vocabularies, built on top of existing technologies and standards, that can be used to represent such tools in Web pages and applications. The goal of the specification is to make it easier to discover. Version 1.0-RELEASE.<h3>Summary of Changes</h3> <p>Changes since the 0.6-DRAFT</p> <ul> <li>additionalType property deprecated and replaced by applicationCategory.</li><li>example added for the name property.</li></ul>

## Minimum properties

| Name              | Description                          |
| :---------------- | :----------------------------------- |
| description | A short description of the tool.  |
| name | The name of the item.  |
| url | Homepage of the tool. URL of the item.  |
| conformsTo | This is used to state the Bioschemas profile that the markup relates to. The identifier can be the url for the version of this bioschemas class on github: https://github.com/BioSchemas/specifications/blob/master/ComputationalTool/jsonld/ComputationalTool_v1.0-RELEASE.json  |


## Recommended properties

| Name              | Description                          |
| :---------------- | :----------------------------------- |
| applicationSubCategory | Subcategory of the application, e.g. 'Arcade Game'. Use an EDAM:Topic to describe the category of application  |
| applicationCategory | Type of software application, e.g. 'Game, Multimedia'. Please use terms from the 'Tool type' table in the biotools documentation.  |
| softwareVersion | Version(s) of the tool, which this information is valid for. Can also be a comma-delimited list and include hyphen-separated ranges of versions.  |
| featureList | Features or modules provided by this application (and possibly required by other applications). Functionality provided by the tool. Note: Bioschemas have removed Text from the Expected Types.  |
| author | The author of this content or rating. Please note that author is special in that HTML 5 provides a special mechanism for indicating authorship via the rel tag. That is equivalent to this and may be used interchangeably.  |
| citation | Publication about this tool. A citation or reference to another creative work, such as another publication, web page, scholarly article, etc.  |
| license | The license of a software, curated dataset, etc. A license document that applies to this content, typically indicated by URL. Use SPDX list of licenses in form https://spdx.org/licenses/  |


## Optional properties
| Name              | Description                          |
| :---------------- | :----------------------------------- |
| codeRepository | Link to the source code repository of the tool.  |
| input | Specification of a consumed input.  |
| output | Specification of a produced output.  |
| programmingLanguage | The main programming language(s) used to build or execute the tool. Please use terms from the ‘Programming language’ table in the Bio.Tools documentation  |
| downloadUrl | Link(s) to the downloadable(s).  |
| applicationSuite | A suite of tools, to which the tool belongs. The name of the application suite to which the application belongs (e.g. Excel belongs to Office).  |
| softwareHelp | A documentation of the tool.  |
| softwareAddOn | Additional sub-tools (add-ons, plug-ins, tools in a suite, etc.) that are included in the tool or workflow. Additional content for a software application.  |
| operatingSystem | Operating systems on which the tool can be used (without additional wrapping). Operating systems supported (Windows 7, OSX 10.6, Android 1.6). Please use terms from the ‘Operating systems’ table in the biotools documentation  |
| identifier | The identifier property represents any kind of identifier for any kind of <a class="localLink" href="http://schema.org/Thing">Thing</a>, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See <a href="/docs/datamodel.html#identifierBg">background notes</a> for more details.  |
| contributor | A secondary contributor to the CreativeWork or Event.  |
| discussionUrl | A link to the page containing the comments of the CreativeWork.  |
| funder | A person or organization that supports (sponsors) something through some kind of financial contribution.  |
| hasPart | Indicates any software dependency. Indicates an item or CreativeWork that is part of this item, or CreativeWork (in some sense).  |
| isAccessibleForFree | A flag to signal that the tool or the service are available to be used for free.  |
| isBasedOn | A tool or another work which this tool is based on, or is an extension, distribution, or deployment of.  A resource from which this work is derived or from which it is a modification or adaption.  |
| isPartOf | A collection, other than a suite of tools, to which the tool belongs.. Indicates an item or CreativeWork that this item, or CreativeWork (in some sense), is part of.  |
| keywords | Additional keywords or tags important for this tool. Multiple entries are delimited by commas. Keywords or tags used to describe this content. Multiple entries in a keywords list are typically delimited by commas.  |
| provider | The provider organization of a web application, database portal, web service, etc. Note: Bioschemas have removed Person from the Expected Types. The service provider, service operator, or service performer; the goods producer. Another party (a seller) may offer those services or goods on behalf of the provider. A provider may also serve as the seller.  |
| thumbnailUrl | A small image representing the tool, such as an icon. A thumbnail image relevant to the Thing.  |
