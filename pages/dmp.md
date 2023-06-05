---
title: Data Management Plan
layout: about
permalink: /dmp.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

# Data Management Plan and Documentation:  

Haunted Locations in Oregon 

<a href="https://github.com/LIB410-Spring2023/group-1/blob/main/_data/group-metadata-file.csv"target="_blank">Metadata</a>  

<a href="https://github.com/LIB410-Spring2023/group-1/tree/main/objects"target="_blank">Objects</a>  

The *Haunted Locations in Oregon* digital collection documents haunted locations in Oregon and contains 21 images of Oregon ranging from 1855 to 1977. Locations document Willamette Valley, Southern Oregon, and natural locations that illustrate historic buildings, cemeteries, and other natural landmarks.  

Objects were gathered from three public repositories: Oregon Digital, the National Archives, and the Library of Congress. Elements include location information, year of creation, rights, and archival links. Image files were uploaded to a GitHub repository and shared on CollectionBuilder. The metadata .csv was uploaded and an .xml file referenced the objects. The file was uploaded using markup. The collection uses open-source tools and is freely available to the public. 

## Data Curation Methodology 

To create our collection of objects, we searched archival databases for images of haunted locations. We saved the images to our individual Dropbox and documented the metadata in our separate spreadsheets. After we uploaded our objects and their metadata to SharePoint, we created a folder for our images and a metadata spreadsheet. We continued to maintain and update the images and spreadsheets in our Dropbox and created backup copies.

To prepare our objects for our digital collections, we separated our objects from the group a second time. Each group member was responsible for certain objects and kept them in our own Dropbox with our own metadata spreadsheets. After we standardized our spreadsheets and objects to fit our Metadata Application Profile (MAP), we split into pairs and peer-reviewed the other’s data. Using this method, we identified mistakes in our group members’ workflow. Once reviewed, we combined our data into a single spreadsheet and were able to create a .csv file and import it to GitHub as a group. Each of us imported the objects we were responsible for. 

To ensure a timely technical delivery, we adhered to the timetable outlined in the class’s Group Profile Milestones document. Each weekly meeting, we went over the milestones outlined in the document and assessed finished tasks and upcoming deadlines. This process enabled us to develop and maintain a steady, progressive workflow, and we met all our deadlines to ensure our site was active and functional for our June 5th presentation.  

## Technical Team and Expertise 

Individual roles and responsibilities followed the “Norms & Roles” guideline provided in week one. 

**Emily**, *the Project Manager*, kept the group on task and maintained our communication. She coordinated role duties, acted as quality control, and divided the Repository Manager role to remaining members. The mid-term and final report writing were divided among the group and assignments submitted on schedule. 

**Jonathan**, *the Collection Development Manager*, selected our 21 objects and verified rights and licensing. He drafted our collection description and finalized it for publication. He worked with Olivia to convert file formats to .jpgs with Photoshop CS for broad utility. Jonathan provided insight into problematic scenarios of our digital collection and its implementation. 

**Olivia**, *the Object Preservation Manager*, developed file naming standards, identified a file preservation format, transcribed meeting notes, and organized our SharePoint storage. Olivia used CollectionBuilder to make objects adhere to MAP guidelines and data consistency. After Jonathan had selected our objects, she uploaded them to cloud storage. 

**Matt**, *the Metadata Manager*, curated the group’s object inventory to comply with CollectionBuilder and MAP guidelines. He reviewed object descriptions and converted coordinates for uniformity. He supplied HTML to the header in the CollectionBuilder collection. Matt was responsible for technical edits of the final report. 

Members collaborated to produce an .md file for CollectionBuilder and strictly followed MAP guidelines and file formatting. They also administered quality control for the collection by reviewing each other’s contributions to our final project. 

## Standards and Formats 

### Data Types: 

There are 21 objects in this digital collection. Each object is a .jpg file, chosen for convenient use and viewing on the web, ranging from 60 kilobytes to 5 megabytes. The average file size is 659 kilobytes, and the total data is 13.5 megabytes. Images are scaled to 75, 150, or 300 pixels per inch with a preference for higher resolution if a higher resolution image was available in our sources.

### Data Handling: 

Image objects were sourced from Oregon Digital, the National Archives, and the Library of Congress. Once collected, they were converted to .jpg, resized, given new file names according to our MAP guidelines, and given a resource description. All files were hosted on SharePoint and stored in personal Dropbox folders for group access. This allowed group members to prepare specific objects according to their responsibilities.

### Folder Structure: 

Our collection objects were compiled into SharePoint and available to group members: 

    Group1-Objects: The inventory spreadsheet. 

    Object Files: Contains .jpg objects

    Old Object Files: Contains outdated files as a backup. 

 	Each group member was responsible for individual objects in a personal Dropbox. 

### File Naming Convention: 

File names have a “regionname_title_creationdate” format.  Definitions:  

    Region Name: City, County, or Region of image. Most originate from cities.  

    Title: Describes file content.  

    Creation Date: Object creation date. Displays a single year or a YYYYMMDDD format. 

## Privacy and Security 

### Privacy: 

Images, objects, and metadata in our project were reviewed using ethical privacy standards. Additionally, objects were retrieved from public sources of good report. Most depicted no individuals, however two images depicted individuals that could be alive: “Merchant Hotel” and “Pittock Mansion”. These images had low dpi, dismissing identification potential.  

Private property access was examined and noted in the metadata. Two private properties were scrutinized and had no expectation of privacy: “Asahel Bush” and “Pittock Mansion”. The Pittock Mansion went public in 1965 (Pittock Mansion 2018) and “Asahel Bush” in 1953 (Green 2020). All metadata was limited and precluded a privacy breach.    

### Security: 

Our files include objects, spreadsheet inventory, meeting notes, and project documents with backup copies on DropBox, SharePoint, personal laptops and CollectionBuilder and password protected. Ownership rights were reviewed for permissions. And fell under public domain, educational use, or a Creative Commons license. 

## Data Preservation/Retention 

### Period of Data Retention: 

Our digital collection will be made available by June 11, 2023, on CollectionBuilder and GitHub. Data will be maintained in cloud storage on SharePoint and Dropbox.

### Data Dissemination: 

Objects are publicly available on GitHub as .jpg files, along with the metadata. Links are provided for access to archival copies.

### Data Storage and Preservation of Access: 

Objects are viewed as .jpgs and maintained on GitHub, and archival copies provided for Oregon Digital, the National Archives, and the Library of Congress sources. The Archive Wayback Machine was used to archive object sources. Links are provided in the collection. 

### Appendix A: Metadata Application Profile (Thornhill, et al. 2023) 

|  Metadata Element Name | Metadata Element Display Label  | Metadata Element Obligation  |  Controlled Vocabulary | Metadata Element Definition and Data Standard Requirement  | Example |
|---|---|---|---|---|---|
|  objectid |  Not applicable | Required  | No  | A unique string with no spaces or special characters that will be used as an ID in the website. Each objectid property should have a single unique value. This should be a unique, lowercase string with no spaces or special characters as it will be used to form the item’s URL. Underscores (_) and dashes (-) are okay; slashes (/) should NOT be used in this field. | portland_kellsrestaurant_1889 |
| title  | Title  |  Required | No |A name given to the resource. This should be a short, descriptive set of words identifying the item.  Each item may only have one title. Each title property should have a single unique value. | Oregon City, Oregon  |
| filename  | Not applicable  | Required  | No  |  The digital object’s filename including the file extension or a full URL to a file hosted external to your project. The value must match the file's filename in your “objects” directory (filenames are case-sensitive). Important note on external items: URLs to external media should always be secure HTTPS links. Filenaming conventions: Each filename should be an all lowercase unique string with no spaces or special characters. Underscores (_) are okay. | Example value for an item in your project’s “objects” folder: portland_kellsrestaurant_1889.jpg Example value for external item: https://images.nypl.org/index.php?id=1529658&t=w |
| format  |  Format | Required  |  Yes | Indicates the item’s media type. Since CollectionBuilder uses logic based on format to display objects, this is the most important field to ensure the interactive visualizations function correctly. If there are errors or anomalies, some pages will not work. The input for this field should be structured according to MIME type standards, consisting of a type and a subtype concatenated with a slash (/) between them.  | Image: image/jpeg, Document: application/pdf, Audio: audio/mp3, Video: video/mp4; image/jpeg  |
| creator  | Creator  | Recommended  | No  | An entity primarily responsible for making the resource. For multiple creators, separate values with a semicolon.  | Carleton E. Watkins  |
| date | Timeline  | Required  |  No |  A point or period of time associated with an event in the lifecycle of the resource. A resource may have several dates associated with it. The date covered by this table refers to the creation of the original resource when the resource was first created before undergoing any conversion.  If the date is unknown, specify an estimated date or date range. | Select one of the following formats for each value: Year: YYYY (1997), Year and month: YYYY-MM (1997-07) Complete date: YYYY-MM-DD (1997-07-16), Example date: 1867 |
| datecreated  | Date Created  | Required  | No  | A point or period of time associated with an event in the lifecycle of the resource. A resource may have several dates associated with it. The date covered by this table refers to the creation of the original resource when the resource was first created before undergoing any conversion.  If the date is unknown, specify an estimated date or date range.  | Select one of the following formats for each value: Date range: YYYY-YYYY, Date estimate: c. YYYY  |
| description  | Description  | Recommended  | No  | An account of the resource. Anything significant about the digital resource not covered elsewhere.  Use standard punctuation and grammar to describe the item’s history, physical appearance, contents, abstract, etc.  | A stenograph depicts a view of Oregon City featuring a mill and buildings  |
| subject  |  Subject | Recommended  | Yes  | The topic(s) of the resource.  For multiple subjects, separate values with a semicolon. |  Pacific Coast; Oregon; Mills |
| location  | Location  |  Recommended | Yes  | A geographic location to which the resource applies.  For multiple locations, separate values with a semicolon.  | Oregon City, OR  |
|  latitude |  Latitude | Recommended  | No  | A geographic coordinate that specifies the north-south position of an item's location.  Expressed as decimal degrees instead of degrees-minutes-seconds format.  Note: Latitude and longitude for your items can be found using Google Maps: Search for a location and right click on the location name. Select the latitude/longitude coordinates displayed at the top of the menu. This will copy the values to your clipboard, allowing you to paste them into your metadata spreadsheet. Latitude will display as the first value and longitude will display as the second value. | 45.3555789490032 |
|  longitude | Longitude  |  Recommended | No  | A geographic coordinate that specifies the east-west position of an item's location. Expressed as decimal degrees instead of degrees-minutes-seconds format. See note above in the latitude section about using Google Maps.   | -122.60635761082   |
| source  |  Source | Recommended  | No | Designates a related source collection or resource from which the object is derived. In such a situation, the name of the collection name and repository would be the input for this field. The input should be expressed as the collection name followed by a comma, then followed by the repository. This element aligns with the “Repository” element identified in your group’s content inventory. The value in your metadata field should be written in HTML where <a href="URL to Item in Source Repository" target="_blank">Display Text Name of Collection - Name of Source Repository</a> Note: Instead of using a comma between the collection and the repository names, please use a hyphen (-). For example, type this into a cell: <a href="https://digitalcollections.nypl.org/items/d1bde300-c52e-012f-bd93-58d385a7bc34" target="_blank">Robert N. Dennis Collection of Stereoscopic Views - The New York Public Library Digital Collections</a> In CollectionBuilder it will render on an item page to look like this: Robert N. Dennis Collection of Stereoscopic Views - The New York Public Library Digital Collections  | <a href="https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99" target="_blank">Robert N. Dennis Collection of Stereoscopic Views - The New York Public Library Digital Collections</a>  |
|  type | Work Type  | Recommended  | Yes  | Distinguish between types using a one- or two-value input. If using a second value, the second value does not need to relate to a controlled vocabulary but should give the further specification of the object type. The two values in a pair should be separated by a semi-colon (`;`).  | Image; Still Image  |
|  rights |  Rights Statement | Required  |  Yes |  A standardized rights statement, not a creativecommons.org license statement, should be used in this field. The value in your metadata field should be written in HTML where <a href="URL to Copyright Statement" target="_blank">Display Text Name of Copyright Statement</a> For example, type this into a cell: <a href="https://rightsstatements.org/page/NoC-US/1.0/" target="_blank">No Copyright - In the United States</a> In CollectionBuilder it will render on an item page to look like this: No Copyright - In the United States | <a href="https://rightsstatements.org/page/NoC-US/1.0/" target="_blank">No Copyright - In the United States</a>  |
|  creativecommons |  Creative Commons License |  Recommended, but could be Required |  Yes | A standardized creative commons license, not a rightsstatement.org rights statement, should be used in this field. The value in your metadata field should be written in HTML where <a href=”URL to Creative Commons license” target=”_blank”>Display Text Name of Creative Commons License</a> For example, type this into a cell: <a href="https://creativecommons.org/publicdomain/mark/1.0/" target="_blank">Public Domain Mark 1.0</a> In CollectionBuilder, it will render on an item page to look like this: Public Domain Mark 1.0  | <a href="https://creativecommons.org/publicdomain/mark/1.0/" target="_blank">Public Domain Mark 1.0</a>  |
| citation  | Citation  | Required  | No  | A citation representing where you got your object from. Use “Citing Artifacts in a Digital Archive” for citation styling. Make sure to add the URL or DOI for the original source’s online location. The value in your metadata field should be written in HTML where "Title," Creator. Date, Repository, Repository Location. Website Name, Collection Name, <a href='URL to Source Repository' target='_blank'>URL to Source Repository</a> Note: For the citation field, you must use single quotes for the URL and target=’_blank’ because the whole value is enclosed in double quotes to account for the commas. For example, type this into a cell: "Oregon City, Oregon," Carleton E. Watkins. 1837, The New York Public Library Digital Collections, New York. NYPL Digital Collections, Robert N. Dennis Collection of Stereoscopic Views, <a href='https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99' target='_blank'>https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99</a> In CollectionBuilder, it will render on an item page to look like this: "Oregon City, Oregon," Carleton E. Watkins. 1837, The New York Public Library Digital Collections, New York. NYPL Digital Collections, Robert N. Dennis Collection of Stereoscopic Views, https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99 | "Oregon City, Oregon," Carleton E. Watkins. 1837, The New York Public Library Digital Collections, New York. NYPL Digital Collections, Robert N. Dennis Collection of Stereoscopic Views, <a href='https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99' target='_blank'>https://digitalcollections.nypl.org/items/510d47e2-699a-a3d9-e040-e00a18064a99</a>  |
| archivedpage  | Archived Page  | Required  | No  | This field must link to the archival record you’ve made using the Wayback Machine’s Save Page Now feature. You should use the Wayback Machine to archive all item pages in your digital collection. The value in your metadata field should be written in HTML where <a href="URL to the Wayback Machine Page" target="_blank">Archived Page</a> For example, type this into a cell: <a href="https://web.archive.org/web/20230428201917/https://digitalcollections.nypl.org/items/d1bde300-c52e-012f-bd93-58d385a7bc34" target="_blank">Archived Page</a> In CollectionBuilder it will render on an item page to look like this: Archived Page | <a href="https://web.archive.org/web/20230428201917/https://digitalcollections.nypl.org/items/d1bde300-c52e-012f-bd93-58d385a7bc34" target="_blank">Archived Page</a>  |



#### Controlled Vocabularies 
| Metadata Element Name | Controlled Vocabularies -  The fields listed below require the use of controlled vocabularies. Use the lists to guide you in the selection of terms that should be applied to each field. |
|---|---|
| subject |  Please use your subject vocabulary list with definitions.
||Art house cinemas - Buildings that house organizations or businesses that present independent films with artistic rather than commercial appeal including foreign or experimental films, or revivals of older releases. http://vocab.getty.edu/page/aat/300412179 |
||Lighthouses – Towers or other structures equipped with a powerful light or lights (originally a signal fire) at the top, erected at important or dangerous points on or near the coast for the guidance of mariners. http://vocab.getty.edu/page/aat/300007741  |
||Cemeteries – In general, areas used for burial or entombment. Specifically, typically refers to relatively large public parks or grounds laid out expressly for the interment of the dead, and not being the yard of any church. Originally the term was derived from the Latin "cœmeterium," referring to Roman underground cemeteries or catacombs. http://vocab.getty.edu/page/aat/300266755 |
||Hotels – Buildings where travellers or tourists are provided with overnight accommodation, meals, and other services; often distinguished from inns and other forms of temporary lodging for travellers by their larger size and range of facilities, in modern times often equipped with a restaurant, bar, conference rooms, and leisure facilities. http://vocab.getty.edu/page/aat/300007166  
||Forts – Permanent fortifications for troops, often surrounded by such elements as ditches, parapets, and ramparts and often used as advance posts in or near hostile territory. Smaller and less heavily fortified than "fortresses."  http://vocab.getty.edu/page/aat/300006909  
||Caves – Natural openings in the earth large enough for human exploration, the largest and most common being those formed by a chemical reaction between circulating groundwater and limestone or dolomite bedrock.  http://vocab.getty.edu/page/aat/300008746
||Mansions – Large imposing, and usually elegant and costly, dwellings. http://vocab.getty.edu/page/aat/300071272  
||Taverns - Primarily 17th- to early 19th-century English and American places of eating, drinking, and public accommodations, which often became local centers of social gatherings; distinguished from "inns" which emphasize their overnight accommodations and also provide food and drinking facilities; for establishments that emphasize drinking, especially liquors, use "pubs" or "saloons."  http://vocab.getty.edu/page/aat/300005207  
||Churches - Buildings for public Christian worship that are distinguished historically from chapels and oratories, which are buildings that are in some respect private, or not public in the widest sense. Church architecture generally somewhat follows standard models, which vary depending upon the date, location, and characteristics of the congregation.  http://vocab.getty.edu/page/aat/300007466  
||Waterfalls - Perpendicular or very steep descents of the water of a stream. May be used for artificial waterfalls only if highly naturalistic in form and context; otherwise prefer "cascades" or "fountains." http://vocab.getty.edu/page/aat/300008736
||Restaurants - Buildings housing businesses where meals or refreshments are sold and eaten.  http://vocab.getty.edu/page/aat/300005182  
||Bridges - Structures spanning and providing passage over waterways, topographic depressions, transportation routes, or similar circulation barriers. http://vocab.getty.edu/page/aat/300007836  
||Highways - Refers to major, high-speed, high-capacity roads between urban areas. The original meaning of "highways" referred to Roman roads that were raised above the ground level; for this meaning, use "elevated roads."   http://vocab.getty.edu/page/aat/300008220  
||Mills - Facilities that spin and weave wool into fabric.  http://vocab.getty.edu/page/aat/300006327  
||Theater - Buildings having a stage or projection screen for the presentation of dramatic performances and providing seating areas for spectators. http://vocab.getty.edu/page/aat/300007117 
||Historic Houses - Houses with architectural, social, or cultural significance; may or may not be officially designated. http://vocab.getty.edu/page/aat/300008064 
||Public (relating to property) - The status or condition of a thing, being, or information being open to general observation, view, or knowledge, or of activties existing, performed, or carried out without concealment.http://vocab.getty.edu/page/aat/300444972 
||Private (relating to property) - The status or condition of a thing, being, or information being available to only a chosen audience, but concealed or safeguarded from general view or knowledge. http://vocab.getty.edu/page/aat/300444973 
|type|DCMI Type Vocabulary: https://www.dublincore.org/specifications/dublin-core/dcmi-type-vocabulary/2003-02-12/  
|Verdana format|MIME Types: https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types/Complete_list_of_MIME_types  
|language| ISO 639-2 Codes for the Representation of Names and Languages: https://www.loc.gov/standards/iso639-2/php/code_list.php  
|location|Oregon – Inhabited by Chinook, Tillamook, Yamel, Northern Paiute, Modoc & many others when Spanish & English arrived in 16th cen.; settled by fur merchants in 18th cen.; great influx of settlers from E arrived in mid-19th cen.  http://vocab.getty.edu/page/tgn/7007708 
||Baker City – city, seat (1868) of Baker county, northeastern Oregon, U.S. It is situated along the Powder River, in Baker Valley, between the Blue Mountains (west) and the Wallowa Mountains (east).  https://www.britannica.com/place/Baker-City 
||Eugene – Located in W Oregon on Willamette River; settled by Eugene Skinner; arrival of railroad stimulated development as lumber & agricultural center.  http://vocab.getty.edu/page/tgn/7014122 
||Florence – Florence is a small city at the mouth of the Siuslaw River, on the Oregon coast.  https://en.wikipedia.org/w/index.php?title=Florence,_Oregon&oldid=1153782909 
||Newport – city, seat (1954) of Lincoln county, western Oregon, U.S. It lies on the north shore of Yaquina Bay at the Pacific Ocean.  https://www.britannica.com/place/Newport-Oregon 
||Portland - city, seat (1854) of Multnomah county, northwestern Oregon, U.S. The state’s largest city, it lies just south of Vancouver, Washington, on the Willamette River near its confluence with the Columbia River, about 100 miles (160 km) by river from the Pacific Ocean.  https://www.britannica.com/place/Portland-Oregon 
||Salem - Located in NW Oregon on Willamette river; missionaries sold homesites to finance the Oregon Institute (1842), a religious school for Amerindians which later became Willamette University; town prospered from traffic on the Oregon Trail.   http://vocab.getty.edu/page/tgn/2085479 
||Seaside – Located in NW Oregon on Pacific Ocean; city named after Seaside House, a historic summer resort built in the 1870s.  https://en.wikipedia.org/w/index.php?title=Seaside,_Oregon&oldid=1154997824 
||Troutdale – Located in NW Oregon at the confluene of the Sandy and Columbia Rivers; city named after pioneer John Harlow’s trout pond in a dale near his residence.  https://en.wikipedia.org/w/index.php?title=Troutdale,_Oregon&oldid=1152615116 
||Warrenton – Warrenton is a small, coastal city in Clatsop County, Oregon, United States. Named for D.K. (Daniel Knight) Warren, an early settler, the town is primarily a fishing and logging community. https://en.wikipedia.org/w/index.p/p?title=Warrenton,_Oregon&oldid=1115706934 
||Wolf Creek – Located in SW Oregon on Wolf Creek; town named for the once abundants wolves in the state. https://en.wikipedia.org/w/index.php?title=Wolf_Creek,_Oregon&oldid=1123215108 
||Crooked River Gorge – Location in Central Oregon; located around Warm Springs and Smith Rock State Park and eroded by the Crooker River.  https://en.wikipedia.org/w/index.php?title=Crooked_River_Gorge&oldid=1146535745 
||Oregon Caves National Monument – Located in SW Oregon; a monument established in 1909 to protect a solutional cave within marble rock.  https://en.wikipedia.org/w/index.php?title=Oregon_Caves_National_Monument_and_Preserve&oldid=1139887486 
||Oregon Coast – Located in W Oregon along the Pacific Ocean.  https://en.wikipedia.org/w/index.php?title=Oregon_Coast&oldid=1153496466 
||U.S. Route 101 – Located on Oregon coast; highway runs from California border to Washington state line at Columbia River. https://en.wikipedia.org/w/index.php?title=U.S._Route_101_in_Oregon&oldid=1151418139 
||Baker County – County of Oregon, USA named for Edward Dickinson Baker, a senator from Oregon who was killed at Ball’s Bluff, a battle of the Civil War in Virginia in 1861.  https://en.wikipedia.org/w/index.php?title=Baker_County,_Oregon&oldid=1143614301 
||Clatsop County – County of Oregon, USA named for the Clatsop tribe of Native Americans who lived along the coast of the Pacific Ocean prior to European settlement.  https://en.wikipedia.org/w/index.php?title=Clatsop_County,_Oregon&oldid=1155356697
||Jefferson County – County of Oregon, USA named for Mount Jefferson after United States president Thomas Jefferson. https://en.wikipedia.org/w/index.php?title=Jefferson_County,_Oregon&oldid=1150976816 
||Josephine County – County of Oregon, USA named for Josephine Rollins Ort, daughter of Floyd Rollins a gold prospector. https://en.wikipedia.org/w/index.php?title=Josephine_County,_Oregon&oldid=1154964059 
||Lane County – County of Oregon, USA named for Joseph Lane, the first governor of the territory. https://en.wikipedia.org/w/index.php?title=Lane_County,_Oregon&oldid=1154958128 
||Lincoln County – County of Oregon USA named for Abraham Lincoln, 16th president of the United States. https://en.wikipedia.org/w/index.php?title=Lincoln_County,_Oregon&oldid=1155355292 
||Marion County – County of Oregon USA named to honor Francis Marion, a Continental Army general from South Carolina who served in the American Revolutionary War.  https://en.wikipedia.org/w/index.php?title=Marion_County,_Oregon&oldid=1154959419 
||Multnomah County – County of Oregon USA named for the Chinookan word for “lower river” an interperative English spelling of ‘Matlnomaq’.  https://en.wikipedia.org/w/index.php?title=Multnomah_County,_Oregon&oldid=1154709406 
|rights|Rights Statements: https://rightsstatements.org/page/1.0/?language=en  
|creativecommons|Creative Commons Licenses: https://creativecommons.org/licenses/  
|| For objects in the public domain you should use this marking within the Creative Commons field: https://creativecommons.org/publicdomain/mark/1.0/  

 

### Appendix BB: Apparition? 

An incidental observation in one of our objects revealed an anomaly in our “Oregon Caves” object described as the Ghost Chamber. We quickly concluded an apparition could be the only explanation. Our hypothesis postulates the unique stereograph photographic process captured a superimposed bilateral locality. This increased sensitivity to phenomena outside normal or supernormal sensory ranges (e.g., sight, hearing) allowed a special circumstance for the right technology and right timing to record this extremely rare event. 

We are, however, ethically certain the ghost has no expectation of privacy. We present this apparition here, in the name of pseudoscience.  


Figure 1: The above image is the result of stereographic photography filtered through multi-aspect and algorithmic methods via computer processes to enhance the image definition. The identity of the person associated with the apparition remains unknown. 

 

## Works Cited 

Green, Virginia. “Oregon Encyclopedia: Explore - Asahel Bush House” Oregon 	Encyclopedia, The Oregon Historical Society, last updated Sept. 6, 2022, 	https://www.oregonencyclopedia.org/articles/asahel_bush_house/. Accessed 3 June 2023. 

"Pittock Mansion: Our Story - History" Pittock Mansion, Pittock Mansion Society, last updated 2018, www.pittockmansion.org/our-story/history/. Accessed 3 June 2023. 

Thornhill, Kate, Stone, Julia, University of Oregon, University of Idaho Libraries. “Metadata Application Profile (Data Dictionary) Template” Humanities Data Management, LIB410 Week 6, University of Oregon. 

 
