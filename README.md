# ArcGIS Online: Web Mapping with Arcade Expressions
This is the repository with screenshots and Arcade code that was used during the tech-session at the European Developer Summit 2024 in Berlin.

## Session description
Web maps are important building blocks of ArcGIS Online and the ArcGIS Platform, powering the functionality of many apps. Including Arcade expressions in web maps allow you to make maps from simple calculations, functions, data conversions, and brand new representations of your data. In this session, learn how to use Arcade Expressions to determine symbology and values in pop-ups and labels, bringing more flexibility and style to existing datasets.
## Symbology with Arcade (Basic)
![image](https://github.com/user-attachments/assets/1531dc2d-6965-4645-b733-3899603e09c0)
![image](https://github.com/user-attachments/assets/0ab70ee8-f9d8-4907-b0ad-78cf98f2358b)
The Arcade code can be found here:
https://github.com/chgresri/arcigs-online-web-mapping-with-arcade-expressions/blob/48e23f5f177a7a793bbe0f785ed660820c619de6/arcade-symbology-basic
## Popups with Arcade (Intermediate)
![image](https://github.com/user-attachments/assets/b87c8bc2-336e-47e9-9d77-9420817e6c3c)

The first part of the Popup is based on a Text Block, which includes attribute values an an Arcade expression:
![image](https://github.com/user-attachments/assets/a37f92a1-ce6f-48bf-9011-866130cc0f2e)

The second part is based on an Arcade Block which creates an intermediate Popup by combining HMTL with Arcade code:
![image](https://github.com/user-attachments/assets/6f67e16f-8800-49d9-8e69-654a071b52c7)
### Arcade expression for Count of Earthquakes
![image](https://github.com/user-attachments/assets/86ad52b3-27bc-471b-a1c5-41bae82368cc)
The Arcade code can be found here:
https://github.com/chgresri/arcigs-online-web-mapping-with-arcade-expressions/blob/7fa7bdd640f07174c82f924ed1cd58e9cfe9f684/arcade-popup-expression-count-of-earthquakes
### Arcade Block for Intermediate Popup
![image](https://github.com/user-attachments/assets/c5626448-c4ff-41d5-84e7-b32050e5afbf)
The Arcade code can be found here:
https://github.com/chgresri/arcigs-online-web-mapping-with-arcade-expressions/blob/af7c7407e47b99f45d90266b3f9d0ce2064b93e6/arcade-popup-arcade-block-html
## Conditional Language Popups (Advanced)
To test the language change, one can add "&locale=fr" to the URL and hit Enter. This changes the browser language.
![image](https://github.com/user-attachments/assets/e2a69046-4ad1-4122-9f7c-1c03aa104652)
![image](https://github.com/user-attachments/assets/2f93c513-3214-451d-ab47-f2993f4f5be5)
The Arcade code can be found here:
https://github.com/chgresri/arcigs-online-web-mapping-with-arcade-expressions/blob/82befe7b8196039484cfd7909b543cbaf6a06549/arcade-popup-multiple-languages
## Conditional User Units Popups (Advanced)
To test the user units, one can go the the profil settings of your ArcGIS Online account and change the units from US Standard to Metric or vice-versa.
![image](https://github.com/user-attachments/assets/c374a8f3-4cf2-40a0-84ad-2e4301e6a37a)
![image](https://github.com/user-attachments/assets/672469eb-442c-4a49-9644-f8de578e9d6a)
![image](https://github.com/user-attachments/assets/239bdd3c-4931-49f6-a66d-8dc79b79b4d8)
![image](https://github.com/user-attachments/assets/e707b74b-4597-46e0-9b2c-636b1c6f3cea)
The Arcade code can be found here:
https://github.com/chgresri/arcigs-online-web-mapping-with-arcade-expressions/blob/b3771e4fbf35a853e57e61e74d0a35ed56baa0ae/arcade-popup-user-units
## Create a bar chart in the Popup (Advanced)
![image](https://github.com/user-attachments/assets/f2bc940f-d2c2-417a-b641-576a39bc0118)
![image](https://github.com/user-attachments/assets/bfdce869-e981-477d-a68a-6137ca73c8a7)
![image](https://github.com/user-attachments/assets/981de28e-3b88-4379-8452-4d5fa0a57987)
![image](https://github.com/user-attachments/assets/280f9024-7ed3-4bda-9c51-1e961f7d7a77)
The Arcade code can be found here:
https://github.com/chgresri/arcigs-online-web-mapping-with-arcade-expressions/blob/53fdd762469b7b6668e142c44b27c205cee64eaf/arcade-popup-chart
## Create a line chart from data in a related table - Relationship Class (Advanced)
![image](https://github.com/user-attachments/assets/023d34f4-25e1-4db4-be75-34c1cdc14cca)
![image](https://github.com/user-attachments/assets/10fcb57c-7a9b-4037-bc93-65bd43e78183)
The Arcade code can be found here:
https://github.com/chgresri/arcigs-online-web-mapping-with-arcade-expressions/blob/58b7a05f7b81c7f02248c3e5b313265db73b1e45/arcade-popup-line-chart-related-table
## Work with m-values in Popups (Advanced)
![image](https://github.com/user-attachments/assets/0e36e89e-9856-49eb-8a38-e91f9c72f28d)
![image](https://github.com/user-attachments/assets/5c3e4323-8873-48b3-b935-afd6368804ec)
The Arcade code can be found here:
https://github.com/chgresri/arcigs-online-web-mapping-with-arcade-expressions/blob/642dd42ef3cb39500945addfc7818788da77a6e0/arcade-popup-m-value
## Work with m-values in Editing-Forms (Advanced)
The following fields are given:
![image](https://github.com/user-attachments/assets/2caf384b-89b0-4bb2-8db3-3f6b52ae85ce)
### Attribut: Public Transport Line
![image](https://github.com/user-attachments/assets/829c6341-0ff7-47ad-b4d4-e6c8e0229607)
The Arcade code can be found here:
https://github.com/chgresri/arcigs-online-web-mapping-with-arcade-expressions/blob/f22ad493f0b084c5d3492534bfc27fa72d3c6b60/arcade-forms-public-transport-line
### Attribut: Direction
![image](https://github.com/user-attachments/assets/bec934a6-fd4f-43be-9315-6603520f6fb9)
The Arcade code can be found here:
https://github.com/chgresri/arcigs-online-web-mapping-with-arcade-expressions/blob/4ef25ccd207592d72d9af7928fa2f5af556f55af/arcade-forms-direction
### Attribut: First M-Value
![image](https://github.com/user-attachments/assets/66d00d03-7f66-484f-8f06-d97e97052159)
The Arcade code can be found here:
https://github.com/chgresri/arcigs-online-web-mapping-with-arcade-expressions/blob/4a57f8ec32a90a5b701afd110f02bddffccaf813/arcade-forms-firs-m-value
### Attribut: Last M-Value
![image](https://github.com/user-attachments/assets/623b6b99-d980-462b-9fbb-6827f0c1f5e0)
The Arcade code can be found here:
https://github.com/chgresri/arcigs-online-web-mapping-with-arcade-expressions/blob/877dc4012651f9930083b1ba7652498eaf1b3a9d/arcade-forms-last-m-value
