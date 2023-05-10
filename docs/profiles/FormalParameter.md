# FormalParameter profile

## Description
Bioschemas specification for describing a formal parameter in the Life Sciences. Version: 1.0-RELEASE (09 March 2021) 

## Minimum properties

| Name              | Description                          | Cardinality |
| :---------------- | :----------------------------------- | :---------- |
| [name](https://schema.org/name) | The name of the item.  | one |
| [conformsTo](None) | This is used to state the Bioschemas profile that the markup relates to. The identifier can be the url for the version of this bioschemas class on github: https://github.com/BioSchemas/specifications/blob/master/FormalParameter/jsonld/FormalParameter_v1.0-RELEASE.json  | one |


## Recommended properties

| Name              | Description                          | Cardinality |
| :---------------- | :----------------------------------- | :---------- |
| [encodingFormat](https://schema.org/encodingFormat) | URLs to accepted formats.  It is strongly recommented that this be specified. If it is not specified, then nothing should be assumed about the encoding formats of the FormalParameter.  | many |
| [additionalType](https://schema.org/additionalType) | An additional type for the item, typically used for adding more specific types from external vocabularies in microdata syntax. This is a relationship between something and a class that the thing is in. In RDFa syntax, it is better to use the native RDFa syntax - the 'typeof' attribute - for multiple types. Schema.org tools may have only weaker understanding of extra types, in particular those defined externally.  | many |
| [description](https://schema.org/description) | A description of the item.  | one |


## Optional properties
| Name              | Description                          | Cardinality |
| :---------------- | :----------------------------------- | :---------- |
| [defaultValue](https://schema.org/defaultValue) | The default value for the FormalParameter. This is commonly only used for Inputs.  | one |
| [valueRequired](https://schema.org/valueRequired) | If the FormalParameter must be specified. This is commonly only used for Inputs  | one |
| [identifier](https://schema.org/identifier) | The identifier property represents any kind of identifier for any kind of <a class="localLink" href="http://schema.org/Thing">Thing</a>, such as ISBNs, GTIN codes, UUIDs etc. Schema.org provides dedicated properties for representing many of these, either as textual strings or as URL (URI) links. See <a href="/docs/datamodel.html#identifierBg">background notes</a> for more details.  | many |
