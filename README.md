# The Climate is Changing: How is Research?

## Exploring Trends in Climate Articles: 2013 to 2023

## Introduction
Upon the inception of this project, I found myself curious about how the sentiment and
urgency in climate change-related scientific literature has evolved. I myself am conducting
research in climate and, while I plan to maintain an unbiased and professional tone in the
article I write, do feel an increasing sense of urgency as the climate warms more and more.


## Corpus Description
I dug in to creating a corpus but immediately encountered difficulties: most scientific
journals publish PDFs, not JSONs, XMLs, or HTMLs. Through some digging, I found PeerJ, a
journal that publishes every article in XML format, among others.
I'd hoped to explore a wide breadth of time but found that XMLs have only recently begun
to be published - the latest year I found on PeerJ was 2013 - so limited my search to the
decade between 2013 and 2023 in five-year increments.
I needed at least 500,000 observations in my corpus (sequence of word tokens) so wanted to
source about 30 articles from 2013, 2018, and 2023 each for a total of nearly 100 articles.
2013 only had 18 articles on PeerJ, so to compensate, I chose 37 articles from 2018 (first two
pages of search results) and 37 from 2023 (to match 2018).
To ensure relevance to and impact on the field, I origincally filtered articles to have 30 or
more citations, but needed to remove this filter to obtain enough articles per year. I'd hoped
to choose the top 30 most cited articles per year but was unable to do so on PeerJ, so simply
sorted by PeerJ's determination of relevance to the query "climate change". PeerJ's
determiniation of relevance is unclear, and this is something to explore in future project. The
most relevant articles per year, after meeting these described criteria, have then been chosen
to comprise my corpus.

## Findings
I began this project with a curiousity about how sentiment has evolved over time in climate change-based scientific literature. I observed some trends described in the sentiment analysis section of this document, but ultimately, hesitate to deem those the real findings of my project - so far as to have adapted the formal title of my project from Changing Sentiment to Changing Trends in Climate Research, which also reflects the greater scope of work this project ended up encompassing. I am taking this section to describe why.

Of particular interest are the classification of mosquito, black, endemic, soil, and unpublished as negative words. Mosquitos are, of course, annoying to humans, but do play a crucial role in ecosystems; scientists generally believe no species has a positive or negative connation, though in literature, mosquitos may stand for irritating in a metaphor, and they do carry disease that can transmit to humans. Black is a tricky one: throughout literature, one can find references to black as a stand-in for darkness and sadness ('a black mood') but does this stem from racist motivations? (See Heathcliff's terrifying 'black' face described throughout Wuthering Heights as a demon or devil.) In the sentences I saw, black simply described the color of a fin - quite neutral. Soil can mean 'to dirty', so it gets negative sentiment, but as a noun referring to dirt, it is actually quite beneficial, or at the very least neutral! Finally, endemic means native of or to, which is in and of itself a neutral meaning. However, it can often refer to disease and I assume that is why it got classified as negative. Finally, a cheeky note that unpublished can stand in as a nod to the oft-stated "publish or perish" dilemma many scientists face. 

Also of interest are the classification of perennial, tree, and dawn as positive words. A plant, specimen, or trend's perennial existence - as opposed to annual or shorter - is not necessarily a good thing. As noted above, scientists generally try to avoid assigning positive or negative meaning to these descriptors, as what is good for one instance is poor for another, so the application of sentiment here may not be entirely accurate. Trees are, of course, lovely things. They provide shade, filter carbon, serve as homes for legions of species... but they are also not "good" any more than a mosquito is "bad" - each just exists in its own place in an ecosystem. Finally, dawn has many a metaphorical meaning, most if not all positive, but, as per my refrain, is a neutral phenomenon in nature.

Finally, I was fascinated to see that the word scientific has a positive connotation here. The scientific method is often praised as an unbiased way to clearly see the world (see my cluster of data-related words in a plot above). It aims to be neutral - neither positive nor negative - even though scientific advances often help improve the world (or at least humans' experiences in it). Sometimes, as in the case of eugenics or big-sugar funded reseach on (you guessed it) sugar, scientific findings can be falsified or manipulated. (It is worth raising the question of whether this was really science to begin with.) But science at its best has no bias - so why has sentiment analysis classified it as a good word? Is it because the aimed lack of bias is in and of itself a good quality? Or is it a doe-eyed look at what people *think* science is, without a clear understanding of how badly it can go? 

Because of these findings, I hesitate to assign real meaning to the sentiment analysis findings in this project. I can see how mosquito or dawn would be important signifiers of emotional tenor in literature. But in science, many of these words' connotations aim to be stripped away, leaving sentiment analysis bereft in an article's sea of mostly-neutral words. 

Ultimately, I found more trustworthy results in my TF-IDF work. The hypothesis I'd arrived with - that the field would have shifted from being more biologically-based to more technologically-based - was not rejected. 

For example, the TFIDFs for species and for soil are relatively the same, respectively, per year, showing that these are consistently-used terms in climate science, not an exception or development used or phased out year by year. At a very granular level, species and soil are both slightly more important in 2013 and decreases very slightly over the years, which could add credence to my hypothesis and prior findings that climate science has become slightly less biologically-based in favor of more technological, computer/man-made based explorations over the years, but in truth, this difference is too small to make meaningful conclusions or statistically significant ones, especially given that the corpus is relatively small and does not encompass the entirety of climate literature for any given year.


Exploring technological words like blockchain and technology yields similar results: a slight addition of credence to my hypothesis and prior findings but mostly statistically insignificant findings/consistency across the years. I am slightly surprised that blockchain has had such a similar TF-IDF in both 2013 and 2023, since it feels a more recent addition to climate science, but perhaps I am underestimating the technological proficiency of the field at the time (in 2013).


I finally explored words like computer, artifical, intelligence, machine, and learning. I did not expect great findings from this search since artifical and intelligence have a vastly different meaning when separate than when together (same for machine and learning) but thought it was worth a peek. Indeed, TF-IDF is nearly identical (often down to the ten-thousandth's place) for all three years. 

A fascinating discovery was the fact that ai and ml still follow this pattern! I am curious about this, but perhaps I am digging for meaning where there is none here - AI and ML have been in development since before 2013 (though it did not become part of the public consciousness until after 2020 as far as I know), and climate science, with its massive datasets and forward-thinking nature, has always well-poised to take advantage of the latest advancements in science and technology alike.

Finally, I explored terms with the highest TF-IDF per year.

In 2013, those were 
exudates,
deme,
gilli,
girdled,
incubations,
typhoon,
dianthus,
q7q8,
franciscana,
tuxtlas,
xenopus,
swallows,
barn,
girdling,
jacutinga,
haemosporidian,
litterfall,
comau,
adelgid, and 
exudate. 
In 2018, those were ncsm,
bee, fox, mouse, tooth, omnh,
mesquite,
teeth,
bait,
plague,
pallid,
postmortem,
asymmetry,
bees,
shells,
bugs,
lingual,
mesial,
herbicide, and 
2070.  
In 2023, those were blockchain,
symbiodiniaceae,
smart,
ai,
poultry,
thicket,
vaccine,
vaccines,
2022, 
gsh, 
biochar, 
manaus,
kunming,
suzukii,
iot,
fireflies,
transactions,
transaction,
xestospongia, and 
dpf. 

Scientific names dominate the TF-IDF chart in 2013, while species dominate 2018. This differentiation is very interesting. I wonder at the shift from scientific names to common ones. Perhaps an attempt to make science more accessible? In 2023, we see blockchain, iot (internet of things), and vaccines appear, which, to me is unsurprising given their "buzziness" in the past three years. However, we still see scientific names AND common animal names. I wonder at this reintroduction of scientific names in 2023, but it may just be due to small sample size.

Finally, I explored sentence generation with n-grams for each year separately, Overall, the sense of sentences generated is about consistent between years (meaning, each year's generated text has similar levels of nonsensicality vs sensicality). 2013 and 2018 tend to describe typical biological phenomena ("HOW INSECT RESPONSES TO EXPERIMENTAL ROAD SALT AFFECTED THESE PERFORMANCE VARIABLES" in 2013 and "AMBIGUITIES WITHIN THE SYDNEY BASIN BIOREGION AN AREA ECOLOGICALLY IT IS CONCOMITANTLY NOTED THAT DETERMINING THE EVENT SIZE RAINFALL FREQUENCY IS BENEFICIAL GIVEN THE INHERENTLY LOW ABUNDANCE OF VERTEBRATE CLADES PRESERVED AT THESE LOCALITIES DIFFERENT TAPHONOMIC FACTORS ARE ALSO PROVIDED" in 2018). On the flip side, in 2023, we see the first mentions of technologies like software ("4 HOMOLOGY MODELLING 2 THREADING AND 3 CREATE PROGRAMS THAT CATER TO THIS WERE THE DRIVING FACTOR WAS EVALUATED USING MEGA 11 SOFTWARE WITH 1000 BOOTSTRAP REPLICATES USING UFBOOT2 AND THE BOYCE INDEX 093"). These are fascinating findings - climate science, from this very brief foray, seems to have shifted from examining only the natural world to both that and the technological one. 

My overall conclusions very much interset me. My initial goal was to examine sentiment, and there were some interesting findings about negativity in 2018 and overall trust in each year, but I found the words' classifications fit more in a literary sense than in a scientific sense, so ultimately did not put too much weight on my sentiment findings. More strong were my findings about TF-IDF, term frequency, and word importance which, although findings were neither drastic nor statistically examined, validated to some extent my hypothesis that the field would begin to lean more technological (studying recent technology) in 2023 as opposed to 5 or 10 years earlier. Of course, much work remains to be done, and a larger corpus would only help my research, as well as the inclusion of more dates - trying to find HTML that predate 2013, examining dates between 2013 and 2023 not on the five-year mark, and seeing if research from this and last year follow these trends are all great places to take this next.


## Future Directions
- Increase corpus size
- Incorporate statistical significance
- Add other components of an analysis of text as data
