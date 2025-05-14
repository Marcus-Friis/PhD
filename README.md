# PhD?

## Interview prep

* Thoroughly read my application
* Create a slide

### Script

##### Why audio visual disinformation (1 min)

* In Trump's presendential campaign, supporters spread fake images of trump receiving support from black voters. 
* Despite easy debunking, it highlights how visual content can be easily created and spread with the intent to mislead.
* Other notable example is from trump's truth social, with him as the pope
* Romanian election subject to TikTok campaigns, leading to calin georgescu gaining large support
* These cases highlight how information and mis/disinormation are increasingly audio visual, spread through modern platforms algorithims, and have huge reach
* This aligns with the paradigm shift in social media consumption, wiht the popularity of TikTok and Instagram embodying the shift towards video platforms (particularly heavily algorithmically curated) 

##### The specific problem (2 min)

* Disinformation and modern content in general is audio visual
* Previously applied methods (on textual platforms e.g. facebook, twitter) are insufficient for contemporary disinformation
* We need to combine methods from computer vision, audio processing and natural language processing to analyze the content of videos
* Beyond content analysis methods, videos are highly referential and intertextual (hidden meaning through audio, trends, slang)
* To fully understand content, we need content relationships, we cannot analyze it in isolation

##### Methodological innovation (1.5 min)

* Model contemporary social media as networks using a temporal multilayer model
* Explicit interactions and implicit content relationships
* Model on both a content level but also on a platform level - heterogenous graph with multiple node objects

##### Outcome and impact (0.5 min)

* With this graph model, we can model disinformation in isolation and context
* We can investigate the profileration of disinformation - looking into which linkages are central to its propagation
* The framework opens up for future research into more dynamics of the platforms like polarization, radicalization, algorithmic echochambers etc.
* This is important as these are the largest platforms that the future generation uses, and it aligns with regulations like DSA

#### Old script

Disinformation is a big societal issue, influencing democratic processes, people's knowledge of health etc. Coupled with an increasingly unstable world order, disinformation has never been so prevalent or easily manifactured. This is further exacerbated by tools like generative ai, with ai content flooding social media platforms. Examples of these are seen very recently. Trump has been posting ai images of himself as the pope on truth social. Or back in his presendential campaign, followers posted ai images of trump with black supporters with the intent on misleading others. Outside of trump, other democratic processes have been interferred with as well. In the recent romanian election, calin georgescu has been accussed of having a disinformation campaign on TikTok, leading to him gaining much greater followership. 

This last example is particularly interesting, as it symbolizes the paradigm shift social media has been subject to. Historically, textual platforms like twitter or facebook have been the largest platforms. Now, short form video platforms have taken over, with platforms like TikTok, Instagram and YouTube (Shorts) having huge user bases and scoring the highest in monthly engage time. The shift in medium brings along its own issue, both on a governance level and on a technical level, and it necessitates innovation in analytical approaches to understanding social media. Textual methods are no longer sufficient, as platforms are increasingly visual first. Furthermore, culturally, shortform video platforms are highly referential and intertextual in nature. A lot of content participates in trends, reacts to other content, reuses audio, or follows a narrative format. Furthermore, content can be layered with messages, requiring knowledge of the surrounding ecosystem to fully understand contet, underscoring the need for a relational perspective on content. 

These factors leads us to this proposed project. We propose modeling short form video platforms as multilayer temporal networks. Multiple layers are used to represent different types of relations between entities. This allows us to effectively capture the relational nature of content and apply network methods in downstream analytical and machine learning tasks, as well as investigate the properties of the constructed graph model. Developing this framework for modeling shortform video platforms is not only useful for this disinformation task. All quantitative tasks dealing with these platforms will benefit from this perspective, as it is both beneficial for understanding content at scale and in isolation. Quantitative research on these platforms is very limited, there is a pressing need for data, and current methods are inadequate for these videos. 

Developing this framework is the bulk of this project, and it presents many challenges and oppertunities. 

### Potentially interesting cases or sources

* Potential current example [Arizona man shot to death in road rage 'returns' to address his killer](https://www.bbc.com/news/articles/cq808px90wxo)
* TikTok's own [policy on mis/disinformation](https://www.tiktok.com/transparency/en-us/combating-misinformation/)
* [Deceptive Trends: The Societal Impact of Disinformation on TikTok](https://www.internationalaffairs.org.au/australianoutlook/deceptive-trends-the-societal-impact-of-disinformation-on-tiktok/)
	* [The Impact of TikTok’s Engagement Algorithm on Political Polarization](https://www.shiruizhong.com/TheIndependentProject.pdf)
	* [A Dictator’s Son Rewrites History on TikTok in His Bid to Become the Philippines’ Next President](https://time.com/6173757/bongbong-marcos-tiktok-philippines-election/)
* Romanian election
	* [EU investigates TikTok over alleged Russian meddling in Romanian vote](https://www.bbc.com/news/articles/cm2v13nz202o)
	* [Romanian voters again turn to TikTok for guidance in rerun of annulled election](https://www.reuters.com/world/europe/romanian-voters-again-turn-tiktok-guidance-rerun-annulled-election-2025-05-01/)
		> TikTok says it has formed a task force to ensure effective moderation of content and has launched a media literacy campaign to help users spot disinformation. In January, the company said it had blocked more than 116,000 spam accounts from being created in Romania during the second half of December.
	* [TikTok: Protecting the integrity of TikTok during the Romanian elections](https://newsroom.tiktok.com/en-eu/protecting-the-integrity-of-tiktok-during-the-romanian-elections)