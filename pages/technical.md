---
title: Technical Information
layout: about
permalink: /technical.html
---


### Context, Content, and Users
With this context for the project in mind, some functional requirements for the metadata records that will be attached to the content naturally arise. Each component of the collection will need separate metadata profiles. The collection will therefore have multiple metadata entries that may look different depending on the nature of the metadata element. Each interview metadata record will at least need to showcase the interviewee and interviewer, the date of the interview, subjects covered in the interview in addition to the Collection Builder required elements. Each transcript record will need to showcase the same record as the interview so that they can be referenced to each other, but the format will need to be distinctly marked as a text file and not an audio file. Each born-digital photograph (or scan) also needs to be tied to the appropriate interview and transcript, so this record will also need the same elements but to be marked as a jpg or other image file. Additionally, these records will need to be given titles that correspond to the title they are given by the interviewee. A short description of the object/photograph should also be included in the metadata record. Subjects and maps will be added to fulfill project requirements. Controlled vocabularies will be used for the “subjects” portion to enhance user searchability within the collection.

### Documentation of elements

## Required CollectionBuilder elements

# Objectid
	Cardinality: 1 entry per record
	Obligation: Mandatory
	Content guidelines: Entry should start with the name of the interviewer, followed by the type of file in parentheses. If there are multiple objects, the number assigned to the object will follow the object. The file extension should follow the naming convention. 
	Applicable controlled vocabularies: N/A
	Mapping to Dublin Core: “Identifier” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/identifier/
	Example: Darren Bender-Beauregard’s interview would be entered as “Darren_Bender-Beauregard_interview”. Darren’s second object would be entered as “Darren_Bender-Beauregard_object_2”

# Filename
	Cardinality: 1 entry per record
	Obligation: Mandatory
	Content guidelines: The value must exactly match the actual filename of the file in the “objects” directory with the appropriate file extension given the format of the file. 
	Applicable controlled vocabularies: N/A
	Mapping to Dublin Core: “Identifier” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/identifier/
	Example: “Darren_Bender-Beauregard_interview.mp3” for Darren’s interview referenced above. 

# Title
	Cardinality: 1 entry per record
	Obligation: Mandatory
	Content guidelines: Entry should be the interviewee’s name unless partial or full anonymity is requested.
	Applicable controlled vocabularies: N/A
	Mapping to Dublin Core: “Title” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/title/
	Example: Darren Bender-Beauregard interview

# Format 
	Cardinality: 1 entry per record
	Obligation: Mandatory
	Content guidelines: This field indicates the item’s media type, which will vary depending on if it is an interview, transcript, or image. Format should follow controlled vocabulary where available. Can use the list of Internet Media Types provided by Dublin Core. 
	Applicable controlled vocabularies: Internet Media Types (MIME)
•	Common values for this collection will be: audio/mp3; image/jpg, or application/pdf. 
	Mapping to Dublin Core: “Format” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/elements11/format/
	Example: audio/mp3 

## CollectionBuilder visualization elements

# Subjects (subject)
	Cardinality: Up to 10 entries per record.
	Obligation: Mandatory 
	Content guidelines: These entries will be topics related to the item. This field allows for multiple subjects (up to 10), each should be separated by a semicolon (;). Subject entries should be selected using the Library of Congress subject headings. 
	Applicable controlled vocabularies: Library of Congress subject headings
	Mapping to Dublin Core: “Subject” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/elements11/subject/
	Example: pawpaws; persimmons; grafting; mennonite; network; knife; cellphone; homestead; farm; indiana. 

 
# Map (latitude)
	Cardinality: 1 entry per record
	Obligation: Mandatory
	Content guidelines: A geographic coordinate of the interview location specified by the north-south position of the interview site. 
	Applicable controlled vocabularies: N/A
	Mapping to Dublin Core: “Location, Period, or Jurisdiction” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/LocationPeriodOrJurisdiction/
	Example: 38.5562

# Map (longitude)
	Cardinality: 1 entry per record
	Obligation: Mandatory
	Content guidelines: A geographic coordinate of the interview location specified by the east-west position of the interview site.
	Applicable controlled vocabularies: N/A
	Mapping to Dublin Core: “Location, Period, or Jurisdiction” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/LocationPeriodOrJurisdiction/
	Example: -86.4683

## Optional CollectionBuilder elements

# Description (Synopsis):
	Cardinality: 1 entry per record
	Obligation: Optional
	Content guidelines: This field should be a brief summary/synopsis of the interview in 3-5 sentences. It should cover major points of the interview. If being used for an object, it should briefly describe the object and its significance. 
	Applicable controlled vocabularies: N/A
	Mapping to Dublin Core: “Description” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/description/
Example: Darren Bender-Beauregard provides a background on growing up Mennonite on the East Coast before attending Goshen College. He now resides in Paoli, Indiana on Brambleberry Farm, where is family has a homestead and sells pawpaw and persimmon seedlings. Darren describes his knowledge of pawpaws and persimmons, the grafting process, and his agricultural network. 

# Interviewee: 
	Cardinality: 1 entry per record
	Obligation: Optional, but should be used for interview and transcript records.
	Content guidelines: This should be the interviewee’s full or preferred name.
	Applicable controlled vocabularies: N/A
	Mapping to Dublin Core: “Contributor” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/contributor/
	Example: Darren Bender-Beauregard 

# Interviewer:
	Cardinality: 1 entry per record
	Obligation: Optional, but should be used for interview and transcript records
	Content guidelines: This should be the interviewer’s full or preferred name.
	Applicable controlled vocabularies: N/A
	Mapping to Dublin Core: “Creator” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/creator/
	Example: Madison Cissell
