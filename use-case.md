# Main Use Case #

Sarah is a first-year PhD student in biomedicine, writing her thesis on the zika virus. First, she needs to catch up with the literature and build a mental model of the field. With thousands of papers already published on the topic and new ones emerging every day, this is a daunting task.

*For many researchers, the starting point in their quest to conquer an unfamiliar knowledge domain is to turn to their personal favourite search engine, type in the name of the field of interest and start reading at the top of the list. Once you have read through the first few articles (usually highly cited review articles), and followed relevant references, you develop an idea of important journals and authors in the field and adapt your search strategy accordingly. With time and patience, a researcher can thus build a mental model of a field.*

*The problem with this strategy is that it can take weeks, if not months before this mental model emerges. Indeed, in many PhD programs, the first year is devoted to this process. There is also a lot of reading and summarizing involved, but searching for relevant literature usually accounts for a large chunk of the time. Another problem is that the results of the discovery process are usually not shared; they become visible only later as reference lists or reading lists, but again with very little context. Therefore, the discovery process is repeated over and over again, taking away a lot of time and resources from the actual research.*

And that’s where Blaze comes in. Blaze is a collaborative discovery tool that provides a visual representation of this mental model. Sarah types “zika”, her topic of interest, into Blaze.

Blaze now searches the literature using the rOpenSci package “fulltext”, covering PubmedCentral, PLOS, BiomedCentral, arXiv, bioRxiv and Crossref.  Blaze also includes other types of research outputs such as data sets, source code and images via archives like figshare, thus leveraging the variety of resources that open science provides. It then uses a variety of measures derived from fulltext, metadata and usage data to infer similarities between the most relevant items. Blaze uses a variety of clustering and ordination techniques to create a map of the results that show items clustered by sub-topic. Using content mining APIs such as OpenAIRE and ContentMine, Blaze adds additional facts to each paper, e.g. the species that are being mentioned in each paper.

Sarah is presented with an interactive map for this field. Blue bubbles represent the main research areas; the closer two bubbles, the closer they are subject-wise. This gives Sarah an overview of the main areas within the field and an indication how they are related. Thus, she can quickly get a mental model of the field.

Now Sarah starts exploring the map. Blaze uses the well-tested approach of “overview-first, zoom and filter, details-on-demand”, employing and interaction model that she knows from her smartphone. Once she clicks on a research area, she is presented with relevant papers in that area. Sarah can see the metadata of each paper and even read full papers within the same interface.

In the course of her exploration, Sarah identifies a number of articles that warrant their own area. So she goes into edit mode. She adds a new area and drags the papers she found into the newly created bubble. She adds a title and places the area on the map.

*Algorithms are not perfect- therefore, Blaze offers an edit mode to change maps.*

Sarah is interrupted by a message from her supervisor Lauren. Lauren suggests a list of papers related to the zika virus that she has added to their joint Zotero group. Sarah connects Blaze to her Zotero account and imports the papers into her map. Blaze automatically places the new papers on the map and creates additional areas when needed.

*Blaze connects to the open science infrastructure, including Zotero and the Open Science Framework.*

Sarah is done for the day. So she publishes her map for other users to explore and modify on Blaze. She tweets the link: "Hey #biomed community, check out my overview map on the #zika virus: https://t.co/40FJMC3Ez6. Would love to get feedback #phdchat"

*The maps themselves are open. Thus, apart from linking to a map, they can also be embedded on other websites. In addition, the underlying data including the structuring information can be exported in various formats.*

The next day, Sarah fires up her e-mail to see that she has received several notifications on her map. She sees that fellow PhD student Amar has added several papers to her map. 

*The history will be preserved to show the individual contributions of users.*

She also notices that Tom, who is working on a map on Aedes (the genus of mosquito that transmits the zika virus) has included her map, as a sub-map of his.

*Using a combination of automated features and collaboration, Blaze aims to build a comprehensive, layered map of biomedical research. This will save thousands of hours that are currently lost in discovery by biomedical researchers each day, and make researchers aware of resources that they would not have found using traditional means of discovery. It will make biomedical research thus more effective and efficient.*
