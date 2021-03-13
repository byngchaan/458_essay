# Urban Africa
*The African continent is vast and diverse, but one constant holds true across it: a rapid migration from rural areas to expanding cities.*
![alter text](/img/main.png)
___
**Review by Byungchan Lim
3/12/2021
Advanced Digital Geographies**

[link to story map](https://storymaps.arcgis.com/stories/73a4b40120b44a3fb9d6935d53d49330)
___
#### Introduction
When you think of Africa, many people have misconception of the continent. Some still speak of Africa as a country, poor, grassy plains, or thick jungles. Yet, African continent have arguably the most uncivilized natural spectacles and are a staple of the tourism industry for most African countries. What we don't realize as a foreigner is that their daily lives are forming more commonly in urban city. This story map educates you more about how urbanization is rapidly happening throughout African continent. Many countries including Kenya, Uganda, and many more are the leading countries actively striving for faster development of urbanization. In fact, Africa is home to some of the world’s largest megacities with more than 5 million inhabitants.

This story map is developed and created by ESRI’s StoryMaps team. It serves as a education purpose and demonstrations of how story map can be developed. Before we get more in depth on each map shown in the article, maps are mostly centered on African continent with its legends explained in the text which is easily understandable. They also contain user interface, clickable and able to explore more.

The source data they acquired from [Africapolis]( https://africapolis.org/data), a project of the [Sahel and West Africa Club](https://www.oecd.org/swac/) in collaboration with [e-geopolis](http://e-geopolis.org/en/home/)

#### Systematic Architecture
The story map “Urban Africa” presented by ESRI’s StoryMap team presented their geonarratives using HTML, CSS and Javascript for simple and easy way for their learners to follow. The page is not utilizing geo-database system as a storage for the datasets that they are using but rather is directly reading and writing through HTML. The entire webpage is formatted by HTML, styled by CSS, and structured unique scrolling style by javascript.

The webpage is though saved and uploaded in ESRI’s ArcGIS StoryMaps. Interesting code was found in the inspector (figure 1). I have a limited knowledge on what the code is for but based on my research, it has something to do with the cookies setting. According to CookiePro, “OptanonWrapper function listen for a user event and determine script behavior based on the user event. For example, a common use of the the OptanonWrapper function creating the event, OneTrustGroupsUpdated, to push values to the dataLayer after user consent, before page reload or navigation”. Unfortunately, I have not understood fully on this source of code.

The story map allows clients and viewers to interactively click on images, and data on maps. Clicking on images allows them to view it larger, clicking on map data will trigger pop up, and zoom to pre-set area.
| OptanonWrapper function | Pop up example |
| --- | --- |
| ![alter text](/img/cookie.png) | ![alter text](/img/popup.png)|
| Figure 1 | Figure 2 |

#### UI/UX and Web Mapping Design
This story map has done excellent job on design in my opinion. Clean white background without clustered colors making it easy to read. It is particularly easier because the whole page layout stayed in a identical concept. The whole story map consisted with description on left and map displaying data on the right as shown in figure 3. It may seem that it is a small detail, but it is a huge difference. Switching from one style to the other confuses readers and require them to take a moment to understand the structure of the layout.

There are 3 sets of maps and they are all pre-set to same geolocation. When needed to zoom to particular area, it is designed to click as a reader to zoom in and out instead of automated feature. It allows readers to follow along on their own pace. Each map is developed by ESRI’s UI making it quick response to each click. The maps are using light theme as a basemap from ArcGIS.

| <img src="img/format.png" width="800" height="500">  |
| :---|
| Figure 3 |
#### Pros and Cons
Overall is a great story map. Each description on author’s point making is short and simple. Dragging on explanation on the side will lose many of the reader’s attention but the writing technique used is almost simple as a bullet point. Great responsive scrolling up and down with loading various maps, and able to view pop up box to access greater detail. I liked how author divided the story map into three parts: Country level, City level, and Explore the data. It allows readers to start broad and naturally zoom into smaller area.

Because the map contains huge data, pop up seems to be little slow (it may due to my computer). Although each picture embedded are cited, many of the author’s statement are not cited. Since majority of the data are acquired from designated websites as mentioned above, it is reader’s ability to find the credibility of the author’s argument. The most important part to be updated (in my opinion) is the zoom function. ESRI built UI is integrated in these maps as well for zoom in and out with home button to be back to pre-set long/lat. However, if you use your mouse scroll to zoom in and out, you are automatically doing page up and down no matter where your mouse is located in. I think this is a huge miss.

#### Conclusion and Reflection
After World War 2, urbanization around the globe has been rapidly growing. More people started living in cities, move out of town for greater success. Today’s developed countries like US started major urbanization from early 1950s, while Latin America and Asia took place in few decades later. The gap between urbanized countries and developing countries in Asia is huge. After careful review of this story map, I found out that Africa has even more gap. And it is time for their turn for rapid growth in cities. Urbanization in Africa will bring their population together which will create more demand and more jobs. However, urbanization is not only a good thing. Countries in Africa are still in developing phase where their medical is one of the most concerning issues. As we learned our lesson from recent Covid-19 outbreak, people disease is going to happen again in the future. Clustered in one area will worsen the situation.

Geovisualization allows decision makers to quickly adapt to current situation. If I was in a decision making position, I would highly invest in inventing effective ways to produce clean water first. As shown in the map, more dense population is found near water. 

___
#### Work Cited
CookiePro (2021). *Using the OptanonWrapper Callback Function.* Retrieved from https://community.cookiepro.com/s/article/UUID-29158b4e-22f6-0067-aa36-94f3b8cf3561#:~:text=You%20can%20use%20the%20OptanonWrapper,before%20page%20reload%20or%20navigation.
