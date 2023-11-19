---
title: Technical Information
layout: about
permalink: /technical.html
---

# Content, Context, and Users

This digital collection consists of six oral history interviews (audio recordings), their corresponding transcripts, 1-5 objects that accompany each interview. These mixtures of interviews, transcripts, and object files are the content of the digital collection. Some of the interviewees are faculty at Indiana University, some farmers, some community members with trees on their property, and some are professionals who work with these fruits as part of their foodways-focused careers.

This collection was built for those who are interested in learning about the different ways pawpaws and persimmons are used in material culture. This digital space was also envisioned to be a place where farmers can listen to stories about the growing, grafting, and cultivation processes that their peers utilize in their own efforts of cultivation. Some interviews will also touch on folkways related to pawpaws and persimmons, and these recordings could be of interest to those interested in foodways folklore. With further development, this collection could be built into a learning commons about native foodways. The oral histories highlight multiple perspectives and relationships to the fruits, making it a landing site for an audience with a plethora of interests and specialties as they relate to pawpaws and persimmons. 

Although pawpaws and persimmons are known colloquially throughout southern Indiana and neighboring Kentucky and Ohio, these fruits are widely unknown on a national and international level (except for those familiar with the Asian persimmon). Even folks who reside in the Ohio Valley may have a basic understanding of the fruits and their flavor, not many are privvy to the folklore and lifeways of those who interact with the fruits. I was first introduced to pawpaws by my grandfather, who grows them in a grove in Louisville, Kentucky. He has had success with his fruits, and their uniqueness and invisibility in American/Midwestern-Southern culture, despite their indigeneity to this very region, has driven me to create this commons for all things pawpaws and persimmons.

# Documentation of elements

## Required CollectionBuilder elements

### Objectid
<ul>
<li> Cardinality: 1 entry per record </li>
<li> Obligation: Mandatory </li> 
<li> Content guidelines: Entry should start with the name of the interviewer, followed by the type of file in parentheses. If there are multiple objects, the number assigned to the object will follow the object. The file extension should follow the naming convention. </li>
<li> Applicable controlled vocabularies: N/A </li>
<li> Mapping to Dublin Core: “Identifier” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/identifier/ </li>
<li> Example: Darren Bender-Beauregard’s interview would be entered as “Darren_Bender-Beauregard_interview”. Darren’s second object would be entered as “Darren_Bender-Beauregard_object_2”. </li>
</ul>

### Filename 
<ul>
<li> Cardinality: 1 entry per record </li>
<li> Obligation: Mandatory </li>
<li> Content guidelines: The value must exactly match the actual filename of the file in the “objects” directory with the appropriate file extension given the format of the file.  </li>
<li> Applicable controlled vocabularies: N/A </li>
<li> Mapping to Dublin Core: “Identifier” 	https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/identifier/
<li> Example: “Darren_Bender-Beauregard_interview.mp3” for Darren’s interview referenced above. </li>
</ul>  

### Title
<ul> 
<li> Cardinality: 1 entry per record </li>
<li> Obligation: Mandatory </li>
<li> Content guidelines: Entry should be the interviewee’s name unless partial or full anonymity is requested. </li>
<li> Applicable controlled vocabularies: N/A </li>
<li> Mapping to Dublin Core: “Title” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/title/ </li>
<li> Example: Darren Bender-Beauregard interview </li>
</ul>  

### Format  
<ul>
<li> Cardinality: 1 entry per record </li>
<li> Obligation: Mandatory </li>
<li> Content guidelines: This field indicates the item’s media type, which will vary depending on if it is an interview, transcript, or image. Format will follow a controlled vocabulary, which will utilize a list of Internet Media Types provided by Dublin Core. </li>
<li> Applicable controlled vocabularies: Internet Media Types (MIME). Common values for this collection will be: audio/mp3; image/jpg, or application/pdf. </li>
<li> Mapping to Dublin Core: “Format” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/elements11/format/ </li>
<li> Example: audio/mp3 </li>
</ul>  

## CollectionBuilder visualization elements

#### Subjects (subject)	
<ul>
<li> Cardinality: Up to 10 entries per record. </li>
<li> Obligation: Mandatory </li>
<li> Content guidelines: These entries will be topics related to the item. This field allows for multiple subjects (up to 10), each should be separated by a semicolon (;). Subject entries should be selected using the Library of Congress subject headings, which is a controlled vocabulary. </li>
<li> Applicable controlled vocabularies: Library of Congress subject headings </li>
<li> Mapping to Dublin Core: “Subject” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/elements11/subject/ </li>
<li> Example: pawpaws; persimmons; grafting; mennonite; network; knife; cellphone; homestead; farm; indiana. </li>
</ul>  

### Map (latitude)
<ul> 
<li> Cardinality: 1 entry per record </li>
<li> Obligation: Mandatory  </li>
<li> Content guidelines: A geographic coordinate of the interview location specified by the north-south position of the interview site. </li>
<li> Applicable controlled vocabularies: N/A </li>	
<li> Mapping to Dublin Core: “Location, Period, or Jurisdiction” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/LocationPeriodOrJurisdiction/  </li>
<li> Example: 38.5562 </li>
</ul>  

### Location
<ul> 
<li> Cardinality: 1 entry per record </li>
<li> Obligation: Mandatory </li>
<li> Content guidelines: The name of the city or town of the interview location, followed by the federally recognized two-letter state and territory abbreviation. </li>
<li> Applicable controlled vocabularies: N/A </li>
<li> Mapping to Dublin Core: “Location, Period, or Jurisdiction” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/LocationPeriodOrJurisdiction/ </li>
<li> Example: Paoli, IN </li>
</ul>  

### Map (longitude)
<ul>
<li> Cardinality: 1 entry per record </li>
<li> Obligation: Mandatory </li>
<li> Content guidelines: A geographic coordinate of the interview location specified by the east-west position of the interview site. </li>
<li> Applicable controlled vocabularies: N/A </li>
<li> Mapping to Dublin Core: “Location, Period, or Jurisdiction” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/LocationPeriodOrJurisdiction/ </li>
<li> Example: -86.4683  </li>
</ul>  

## Optional CollectionBuilder elements

### Description (Synopsis):
<ul> 
<li> Cardinality: 1 entry per record </li>
<li> Obligation: Optional </li>
<li> Content guidelines: This field should be a brief summary/synopsis of the interview in 3-5 sentences. It should cover major points of the interview. If being used for an object, it should briefly describe the object and its significance. </li>
<li> Applicable controlled vocabularies: N/A </li>
<li> Mapping to Dublin Core: “Description” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/description/ </li>
<li> Example: Darren Bender-Beauregard provides a background on growing up Mennonite on the East Coast before attending Goshen College. He now resides in Paoli, Indiana on Brambleberry Farm, where is family has a homestead and sells pawpaw and persimmon seedlings. Darren describes his knowledge of pawpaws and persimmons, the grafting process, and his agricultural network. </li>
</ul>  

### Interviewee: 
<ul>
<li> Cardinality: 1 entry per record </li>
<li> Obligation: Optional, but should be used for interview and transcript records. </li>
<li> Content guidelines: This should be the interviewee’s full or preferred name.  </li>
<li> Applicable controlled vocabularies: N/A </li>
<li> Mapping to Dublin Core: “Contributor” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/contributor/ </li>
<li> Example: Darren Bender-Beauregard </li>
</ul>  

### Interviewer:
<ul>
<li> Cardinality: 1 entry per record </li>
<li> Obligation: Optional, but should be used for interview and transcript records. </li>
<li> Content guidelines: This should be the interviewer’s full or preferred name. </li>
<li> Applicable controlled vocabularies: N/A  </li>
<li> Mapping to Dublin Core: “Creator” https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/creator/ </li>
<li> Example: Madison Cissell </li> 
</ul>  

## Documentation of all elements
<table>
<tr>
<th> Metadata Element </th>
<th> Cardinality </th>
<th> Obligation	</th>
<th> Content Guidelines </th>
<th> Applicable Controlled Vocabularies  </th>
<th> Mapping to Dublin Core  </th>
<th> Dublin Core Link </th>
<th> Example </th>
</tr> 
<tr>
<td> Objectid </td>
<td> 1 entry per record </td>
<td> Mandatory </td>
<td> Entry should start with the name of the interviewer, followed by the type of file in parentheses. If there are multiple objects, the number assigned to the object will follow the object. The file extension should follow the naming convention. 
<td> N/A </td>
<td> "Identifier"	</td>
<td> https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/identifier/	</td>
<td> Darren Bender-Beauregard’s interview would be entered as “Darren_Bender-Beauregard_interview”. Darren’s second object would be entered as “Darren_Bender-Beauregard_object_2” </td>
</tr>
<tr>
<td> Filename </td>
<td> 1 entry per record	</td>
<td> Mandatory	</td>
<td> The value must exactly match the actual filename of the file in the “objects” directory	</td>
<td> N/A </td>
<td> "Identifier" </td>
<td> https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/identifier/ </td>
<td> “Darren_Bender-Beauregard_interview.mp3” for Darren’s interview referenced above. </td> 
</tr>
<tr>
<td> Title	</td>
<td> 1 entry per record </td>
<td> Mandatory	Entry should be the interviewee’s name unless partial or full anonymity is requested. </td>
<td> N/A	</td>
<td> "Title"	</td>
<td> https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/title/	</td>
<td> Darren Bender-Beauregard </td>
</tr>
<tr> 
<td> Format	</td>
<td> 1 entry per record	</td>
<td> Mandatory	</td>
<td> This field indicates the item’s media type, which will vary depending on if it is an interview, transcript, or image. </td>
<td> Format should follow controlled vocabulary where available. Can use the list of Internet Media Types provided by Dublin Core.	</td>
<td> Internet Media Types (MIME). Common values for this collection will be: audio/mp3; image/jpg, or application/pdf. </td>
<td> "Format"	</td>
<td> https://www.dublincore.org/specifications/dublin-core/dcmi-terms/elements11/format/ </td>
<td> audio/mp3 </td>
</tr>
<tr> 
<td> Subject </td>
<td> Up to 10 entries per record </td>
<td> Mandatory	</td>
<td> These entries will be topics related to the item. This field allows for multiple subjects (up to 10), each should be separated by a semicolon (;). Subject entries should be selected using the Library of Congress subject headings. </td>
<td> Library of Congress subject headings	</td>
<td> "Subject" </td>
<td> https://www.dublincore.org/specifications/dublin-core/dcmi-terms/elements11/subject/ </td>
<td> pawpaws; persimmons; grafting; Mennonite; network; knife; cellphone; homestead; farm; Indiana. </td>
</tr>
<tr> 
<td> Latitude	</td>
<td> 1 entry per record	</td>
<td> Mandatory	</td>
<td> A geographic coordinate of the interview location specified by the north-south position of the interview site. </td>
<td> N/A	</td>
<td> “Location, Period, or Jurisdiction”	</td>
<td> https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/LocationPeriodOrJurisdiction/	</td>
<td> 38.5562 </td>
</tr>
<tr> 
<td> Longitude	</td>
<td> 1 entry per record </td>
<td> Mandatory </td>
<td> A geographic coordinate of the interview location specified by the east-west position of the interview site. </td>
<td> N/A	</td>
<td> “Location, Period, or Jurisdiction”	</td>
<td> https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/LocationPeriodOrJurisdiction/	</td>
<td> 86.4683 </td>
</tr>
<tr>
<td> Location	</td>
<td> 1 entry per record </td>
<td> Mandatory	</td>
<td>The name of the city or town of the interview location, followed by the federally recognized two-letter state and territory abbreviation.	</td>
<td> N/A	</td>
<td> “Location, Period, or Jurisdiction” </td>
<td> https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/LocationPeriodOrJurisdiction/	</td>
<td> Paoli, IN </td>
</tr>
<tr>
<td> Description </td>	
<td> 1 entry per record	</td>
<td> Optional	</td>
<td> This field should be a brief summary/synopsis of the interview in 3-5 sentences. It should cover major points of the interview. </td>
<td> N/A	</td>
<td> "Description"	</td>
<td> https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/description/	</td>
<td> Darren Bender-Beauregard provides a background on growing up Mennonite on the East Coast before attending Goshen College. He now resides in Paoli, Indiana on Brambleberry Farm, where is family has a homestead and sells pawpaw and persimmon seedlings. Darren describes his knowledge of pawpaws and persimmons, the grafting process, and his agricultural network. </td>
</tr>
<tr> 
<td> Interviewee	</td>
<td> 1 entry per record </td>
<td> Optional, but should be used for interview and transcript records.	</td> 
<td> This should be the interviewee’s full or preferred name.	</td>
<td> N/A	</td>
<td> "Contributor"	</td>
<td> https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/contributor/	</td>
<td> Darren Bender-Beauregard </td>
</tr>
<tr>
<td> Interviewer	</td>
<td> 1 entry per record	</td>
<td> Optional, but should be used for interview and transcript records. </td>	
<td> This should be the interviewer’s full or preferred name. </td>	
<td> N/A	</td>
<td> "Creator"	</td>
<td> https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/creator/ </td>
 <td> Madison Cissell </td>
</tr>
</table>
