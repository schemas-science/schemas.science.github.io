# DataCatalog profile

## Description
A guide for how to describe data catalogs/repositories in the life-sciences using Schema.org-like annotation. Version 0.3-RELEASE-2019_07_01

## Minimum properties

| Name              | Description                          |
| :---------------- | :----------------------------------- |
| description | A description of the item.  |
| name | The name of the item.  |
| url | URL of the item.  |
| keywords | Keywords or tags used to describe this content. Multiple entries in a keywords list are typically delimited by commas.  |
| provider | The service provider, service operator, or service performer; the goods producer. Another party (a seller) may offer those services or goods on behalf of the provider. A provider may also serve as the seller.  |
| conformsTo | This is used to state the Bioschemas profile that the markup relates to. The identifier can be the url for the version of this bioschemas class on github: https://github.com/BioSchemas/specifications/blob/master/DataCatalog/jsonld/DataCatalog_v0.3-RELEASE-2019_07_01.json  |


## Recommended properties

| Name              | Description                          |
| :---------------- | :----------------------------------- |
| dataset | A dataset contained in this catalog.  |
| alternateName | An alias for the item.  |
| identifier | The identifier property represents any kind of identifier for any kind of <a class="localLink" href="http://schema.org/Thing">Thing</a>, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See <a href="/docs/datamodel.html#identifierBg">background notes</a> for more details.  |
| about | The subject matter of the content.  |
| citation | A citation or reference to another creative work, such as another publication, web page, scholarly article, etc.  |
| dateCreated | The date on which the CreativeWork was created or the item was added to a DataFeed.  |
| license | A license document that applies to this content, typically indicated by URL.  |
| sourceOrganization | The Organization on whose behalf the creator was working.  |


## Optional properties
| Name              | Description                          |
| :---------------- | :----------------------------------- |
| dateModified | The date on which the CreativeWork was most recently modified or when the item's entry was modified within a DataFeed.  |
| encodingFormat | Media type typically expressed using a MIME format (see <a href="http://www.iana.org/assignments/media-types/media-types.xhtml">IANA site</a> and <a href="https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types">MDN reference</a>) e.g. application/zip for a SoftwareApplication binary, audio/mpeg for .mp3 etc.).<br/><br/>  In cases where a <a class="localLink" href="http://schema.org/CreativeWork">CreativeWork</a> has several media type representations, <a class="localLink" href="http://schema.org/encoding">encoding</a> can be used to indicate each <a class="localLink" href="http://schema.org/MediaObject">MediaObject</a> alongside particular <a class="localLink" href="http://schema.org/encodingFormat">encodingFormat</a> information.<br/><br/>  Unregistered or niche encoding and file formats can be indicated instead via the most appropriate URL, e.g. defining Web page or a Wikipedia/Wikidata entry.  |
