# CourseInstance profile

## Description
Specification describing the instance of a course.  This specification can be used in tandem with a Course. A course is used to describe the broad, common aspects of a recurring training event - whereas a course instance is about the specific times and location of when that course is held. <h4>Summary of Changes</h4>    No changes since 0.9-DRAFT of the CourseInstance profile. Version: 1.0-RELEASE (13 September 2022)

## Minimum properties

| Name              | Description                          | Cardinality |
| :---------------- | :----------------------------------- | :---------- |
| [courseMode](https://schema.org/courseMode) | The medium or means of delivery of the course instance or the mode of study, either as a text label (e.g. 'online', 'onsite' or 'blended'; 'synchronous' or 'asynchronous'; 'full-time' or 'part-time') or as a URL reference to a term from a controlled vocabulary (e.g. https://ceds.ed.gov/element/001311#Asynchronous ).   The medium, means or pace of delivery of the course instance or the mode of study, either as a text label (e.g. 'online', 'onsite', 'hybrid' or 'blended'; 'synchronous' or 'asynchronous'; 'full-time' or 'part-time') or as a URL reference to a term from a controlled vocabulary (e.g. https://ceds.ed.gov/element/001311#Asynchronous ).   Another example of a Glossary of terms as defined by the Bioschemas Training community and published in Zenodo in 2016: https://zenodo.org/record/166378#.YrHnEi8iu-o.  | many |
| [location](https://schema.org/location) | Location of the Course Instance. If the Course Instance is online, add the connection details as text The location of for example where the event is happening, an organization is located, or where an action takes place.  | one |
| [conformsTo](None) | This is used to state the Bioschemas profile that the markup relates to. The identifier can be the url for the version of this bioschemas class on github: https://github.com/BioSchemas/specifications/blob/master/CourseInstance/jsonld/CourseInstance_v1.0-RELEASE.json  | many |


## Recommended properties

| Name              | Description                          | Cardinality |
| :---------------- | :----------------------------------- | :---------- |
| [endDate](https://schema.org/endDate) |  The end date and time of the item (in ISO 8601 date format).  | one |
| [inLanguage](https://schema.org/inLanguage) |  The language of the content or performance or used in an action. Please use one of the language codes from the IETF BCP 47 standard. See also availableLanguage. Supersedes language.  | one |
| [instructor](https://schema.org/instructor) | An instructor can be the main teacher or trainer, as well as a training assistant, or a helper. A person assigned to instruct or provide instructional assistance for the CourseInstance.  | many |
| [offers](https://schema.org/offers) | An offer to provide this item—for example, an offer to sell a product, rent the DVD of a movie, perform a service, or give away tickets to an event. Use businessFunction to indicate the kind of transaction offered, i.e. sell, lease, etc. This property can also be used to describe a Demand. While this property is listed as expected on a number of common types, it can be used in others. In that case, using a second type, such as Product or a subtype of Product, can clarify the nature of the offer. Inverse property: itemOffered.   Bioschemas: The price an attendee would pay to attend this CourseInstance. The price currency can be for instance in 'GBP' (pound sterling) or 'CHF' (Swiss francs).  | many |
| [startDate](https://schema.org/startDate) |  The start date and time of the item (in ISO 8601 date format).  | one |
| [url](https://schema.org/url) | The preferred URL of this course instance. You must provide this value if it is known URL of the item.  | one |


## Optional properties
| Name              | Description                          | Cardinality |
| :---------------- | :----------------------------------- | :---------- |
| [alternateName](https://schema.org/alternateName) |  An alias for the item.  | many |
| [contributor](https://schema.org/contributor) | Contributors are those who made non-authorship contributions: e.g., critical review, commentary or revision. A secondary contributor to the CreativeWork or Event.  | many |
| [description](https://schema.org/description) | A description of the Course Instance.   (courseInstance) description can be used to override (course) description for specific course instances. A description of the item.  | one |
| [duration](https://schema.org/duration) | (CourseInstance) duration can be used to override (Course) duration for specific course instances. The duration of the item (movie, audio recording, event, etc.) in ISO 8601 date format.  | one |
| [eventStatus](https://schema.org/eventStatus) | An eventStatus of an event represents its status; particularly useful when an event is cancelled or rescheduled.   An eventStatus of an event represents its status; particularly useful when an event is cancelled or rescheduled. Used as text label (e.g. 'postponed', 'cancelled', 'date TBC', 'application open' or 'registration closed').  | one |
| [funder](https://schema.org/funder) |  A person or organization that supports (sponsors) something through some kind of financial contribution.  | many |
| [image](https://schema.org/image) |  An image of the item. This can be a URL or a fully described ImageObject.  | one |
| [maximumAttendeeCapacity](https://schema.org/maximumAttendeeCapacity) |  The total number of individuals that may attend an event or venue.  | one |
| [name](https://schema.org/name) | The name of the course.  Course instance name can be used to override Course name for variations in specific Course instances. Use name from Course unless the Course instance has a different name from the course. The name of the item.  | one |
| [organizer](https://schema.org/organizer) |  An organizer of an Event.  | many |
| [subEvent](https://schema.org/subEvent) | For events within events e.g. guest lecture within a workshop event An Event that is part of this event. For example, a conference event includes many presentations, each of which is a subEvent of the conference. Supersedes subEvents. Inverse property: superEvent.  | many |
| [superEvent](https://schema.org/superEvent) | Use to describe the event a course instance takes place within. e.g. Galaxy Workshop during the ISMB Conference.  An event that this event is a part of. For example, a collection of individual music performances might each have a music festival as their superEvent. Inverse property: subEvent.  | many |
| [workFeatured](https://schema.org/workFeatured) | A work featured in some event, e.g. exhibited in an ExhibitionEvent. Specific subproperties are available for workPerformed (e.g. a play), or a workPresented (a Movie at a ScreeningEvent).   The training material used in this specific course instance, or produced for this course instance. If this is the same for all Course Instances, use hasPart and/or mentions in Course instead  | many |
