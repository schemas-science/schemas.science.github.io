# Course profile

## Description
Specification describing a course.  This specification must be used in tandem with a courseInstance. A course is used to describe the broad, common aspects of a recurring training event - whereas a course instance is about the specific times and location of when that course is held. <h4>Summary of Changes</h4>    No changes since 0.10-DRAFT of the Course profile.</li>         </ul> Version: 1.0-RELEASE (13 September 2022) 

## Minimum properties

| Name              | Description                          |
| :---------------- | :----------------------------------- |
| description |  A description of the item.  |
| keywords | Free text keywords delimited by commas describing the Course content. Keywords or tags used to describe this content. Multiple entries in a keywords list are typically delimited by commas.  |
| name |  The name of the item.  |
| conformsTo | This is used to state the Bioschemas profile that the markup relates to. The identifier can be the url for the version of this bioschemas class on github: https://github.com/BioSchemas/specifications/blob/master/Course/jsonld/Course_v1.0-RELEASE.json  |


## Recommended properties

| Name              | Description                          |
| :---------------- | :----------------------------------- |
| about | The subject of this Course. 
Use the DefinedTerm type to add a controlled vocabulary term to categorise the course (such as using the [EDAM Topic ontology](https://bioportal.bioontology.org/ontologies/EDAM/?p=classes&conceptid=http%3A%2F%2Fedamontology.org%2Ftopic_0003)). The subject matter of the content.
Inverse property: subjectOf.  |
| abstract | An abstract is a short description that summarizes a Course An abstract is a short description that summarizes a CreativeWork  |
| aggregateRating |  The overall rating, based on a collection of reviews or ratings, of the item.  |
| citation |  A citation or reference to another creative work, such as another publication, web page, scholarly article, etc.  |
| coursePrerequisites |  Requirements for taking the Course. May be completion of another Course or a textual description like "permission of instructor". Requirements may be a pre-requisite competency, referenced using AlignmentObject.  |
| educationalLevel | The level expected to be able to participate in the course. Examples of educational levels include 'beginner', 'intermediate' or 'advanced'. The level in terms of progression through an educational or training context. Examples of educational levels include 'beginner', 'intermediate' or 'advanced', and formal sets of level indicators.  |
| hasCourseInstance | A course may be ran multiple times in different locations or at different times. Use hasCourseInstance to list the offerings of this Course.

Please see the [Course Instance specification](https://bioschemas.org/specifications/CourseInstance) for the full list of properties. An offering of the course at a specific time and place or through specific media or mode of study or to a specific section of students.  |
| license | If the Course has an open-source license, include the short URL, as found in OSI. Otherwise use CreativeWork to describe your custom license. A license document that applies to this content, typically indicated by URL.  |
| mentions | Datasets, tools, technologies, entities etc, which are actively used by and/or referred to by this course.

If this varies in a *CourseInstance*, use the *CourseInstance* version of _mentions_ to override this mentions. Indicates that the CreativeWork contains a reference to, but is not necessarily about a concept.  |
| provider | The organization responsible for providing the educational input for the course, e.g. content, assessments, accreditation etc.
Note: providing a course goes beyond creating it as it implies some degree of academic responsibility for accrediting the content of the course, perhaps running assessments etc. The service provider, service operator, or service performer; the goods producer. Another party (a seller) may offer those services or goods on behalf of the provider. A provider may also serve as the seller. Supersedes carrier.  |
| teaches | Statements that describe what knowledge, skills or abilities students should acquire on completion of this Course The item being described is intended to help a person learn the competency or learning outcome defined by the referenced term.  |
| timeRequired | Approximate or typical time it takes to work through this learning resource for the typical intended target audience, e.g. 'P30M', 'P1H25M'. This should use the ISO 8601 duration format. 

If this varies in a *CourseInstance*, use _duration_ in *CourseInstance* to override timeRequired. Approximate or typical time it takes to work with or through this learning resource for the typical intended target audience, e.g. 'P30M', 'P1H25M'.  |
| url | The preferred URL of the course page. You must provide this value if it is known. URL of the item.  |


## Optional properties
| Name              | Description                          |
| :---------------- | :----------------------------------- |
| accessibilitySummary | A human-readable summary of specific accessibility features or deficiencies within the course. A human-readable summary of specific accessibility features or deficiencies, consistent with the other accessibility metadata but expressing subtleties such as "short descriptions are present but long descriptions will be needed for non-visual users" or "short descriptions are present and no long descriptions are needed."  |
| alternateName |  An alias for the item.  |
| audience | The type of audience intended for your course. A succinct description of the attendees.  An intended audience, i.e. a group for whom something was created. Supersedes serviceAudience.  |
| comment |  Comments, typically from users.  |
| commentCount |  The number of comments this CreativeWork (e.g. Article, Question or Answer) has received. This is most applicable to works published in Web sites with commenting system; additional comments may exist elsewhere.  |
| courseCode |  The identifier for the Course used by the course provider (e.g. CS101 or 6.001).  |
| creator | The creator/author of the course. Note, this may be different from the instructor who delivers it (descibed in CourseInstance), or the author who created the training materials used. The creator/author of this CreativeWork. This is the same as the Author property for CreativeWork.  |
| dateCreated |  The date on which the CreativeWork was created or the item was added to a DataFeed.  |
| dateModified |  The date on which the CreativeWork was most recently modified or when the item's entry was modified within a DataFeed.  |
| educationalCredentialAwarded | Strongly recommended if exists. A description of the qualification, award, certificate, diploma or other educational credential awarded as a consequence of successful completion of this course. A description of the qualification, award, certificate, diploma or other educational credential awarded as a consequence of successful completion of this course.  |
| hasPart | A training material used in a course such as an exercise, handouts, or slides. 

Inverse property: isPartOf.

If this varies in a CourseInstance, use workFeatutred to override this property value.  Indicates an item or CreativeWork that is part of this item, or CreativeWork (in some sense).
Inverse property: isPartOf.  |
| image |  An image of the item. This can be a URL or a fully described ImageObject.  |
| isBasedOn | A course, book or other resource on which this Course is based. A resource that was used in the creation of this resource. This term can be repeated for multiple sources. For example, http://example.com/great-multiplication-intro.html. Supersedes isBasedOnUrl.  |
| thumbnailUrl |  A thumbnail image relevant to the Thing.  |
