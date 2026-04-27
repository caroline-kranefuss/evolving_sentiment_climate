# The Climate is Changing: How is Research?

## Exploring Trends in Climate Articles: 2013 to 2023
This project explores a personal interest in climate literature over the past decade - I am curious what trends and changes by half-decade are observed. Will sentiment, urgency, length, and key words change due to increasing pressure on the climate and planet? Or, because science aims to remain unbiased, will little to no changes occur?


## Corpus Description

90 scientific articles are drawn from PeerJ's publications in the decade spanning 2013 to 2023 (30 from 2013, 30 from 2018, and 30 from 2023). Articles are sorted by PeerJ's determination of relevance to the query "climate change." The top 30 most relevant articles per year, after meeting these described criteria, have then been chosen to comprise my corpus.

## Abstract
Upon the inception of this project, I found myself curious about how the sentiment and urgency in climate change-related scientific literature has evolved. I myself am conducting research in climate change, and, while I plan to maintain an unbiased and professional tone in the article I write, do feel an increasing sense of urgency as the climate warms more and more.

I dug in to creating a corpus but immediately encountered difficulties: most scientific journals publish PDFs, not JSONs, XMLs, or HTMLs. Through some digging, I found PeerJ, a journal that publishes every article in XML format, among others.

I'd hoped to explore a wide breadth of time but found that XMLs have only recently begun to be published - the latest year I found on PeerJ was 2013 - so limited my search to the decade between 2013 and 2023 in five-year increments.

I needed at least 500,000 observations in my corpus (sequence of word tokens) so sourced 30 articles from 2013, 2018, and 2023 each for a total of nearly 100 articles.

To ensure relevance to and impact on the field, I origincally filtered articles to have 30 or more citations, but needed to remove this filter to obtain 30 articles per year. I'd hoped to choose the top 30 most cited articles per year but was unable to do so on PeerJ, so simply sorted by PeerJ's determination of relevance to the query "climate change". The top 30 most relevant articles per year, after meeting these described criteria, have then been chosen to comprise my corpus.

## Future Directions
- Increase corpus size
- Incorporate statistical significance
- Add other components of an analysis of text as data
