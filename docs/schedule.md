# Current Class-by-Class Schedule

### Introduction and Overview

8/29 – What does it mean to be practical?

* In class: Syllabus overview, intro/transcription exercise ([slides](slides/class-1.pdf))

9/3 – What can you do with text?

* Before class:
	* Read: Li-Young Lee, “[Persimmons](https://www.poetryfoundation.org/poems/43011/persimmons)”
	* Read: Michael Whitmore, “[Text: A Massively Addressable Object](https://dhdebates.gc.cuny.edu/read/untitled-88c11800-9446-469b-a3be-3fdb36bfbd1e/section/402e7e9a-359b-4b11-8386-a1b48e40425a)”

* In class: Close reading and [Voyant](https://voyant-tools.org/) exercise ([slides](../slides/class-2.pdf))

### Unit 1: Turning Text into Data

9/5 – Platforms and People

* **HW 0 Due:** Install [Anaconda](https://www.anaconda.com/distribution/#download-section) <-- You want the Python 3.7 version

* Before class:
	* Read: Scott Weingart, “[The Route of a Text Message](https://scottbot.net/the-route-of-a-text-message/)”
	* Read: Lilly Irani, “[Justice for ‘Data Janitors’](https://www.publicbooks.org/justice-for-data-janitors/)”

* In class: Intro to Jupyter and discussion of the platforms and people that make data science with text possible ([slides](../slides/class-3.pdf) | [notebook](../notebooks/class3-jupyter-intro.ipynb))

9/10 – Web Scraping

* Before class:
	* Read: Astead Herndon et al.,, “[What Do Rally Playlists Say About the Candidates?](https://www.nytimes.com/interactive/2019/08/19/us/politics/presidential-campaign-songs-playlists.html)”
	* Read: David Zentgraf, “[What Every Programmer Absolutely, Positively Needs to Know about Encodings and Character Sets to Work with Text](http://kunststube.net/encoding/)”

* In class: Web scraping and HTML parsing using Beautiful Soup ([slides](../slides/class4slides.pdf) | [complete notebook](h../notebooks/class4-web-scraping-complete.ipynb) | [class notebook](../notebooks/class4-web-scraping-inclass.ipynb))

9/12 – More Web Scraping

* Before class: Work through the notebook, "class4-web-scraping.ipynb," distributed via Canvas.

* In class: More web scraping ([complete notebook](../notebooks/class5-web-scraping-NYT-complete.ipynb) | [class notebook](../notebooks/class5-web-scraping-NYT-inclass.ipynb))

9/17 – APIs

* Before class: Work through the notebook "class6-accessing-apis-inclass.ipynb," distributed via Canvas.

* In class: More with APIs (accessing APIS: [class notebook](../notebooks/class6-accessing-apis-inclass.ipynb), [complete notebook](../notebooks/class6-accessing-apis-complete.ipynb) | Genius API [class notebook](../notebooks/class6-genius-api-inclass.ipynb), [complete notebook](../notebooks/class6-genius-api-complete.ipynb))

9/19 - Text parsing / regular expressions

* **HW1 Due**: Scrape the song lyrics of one of the candidate's songs from genius.com using Beautiful Soup (assignment on Canvas)

* In class: Text parsing and regex with our candidate song lyrics (regex: [class notebook](../notebooks/class7-regex-intro-inclass.ipynb), [complete notebook](lass7-regex-intro-complete.ipynb) | cleaning song lyrics: [class notebook](../notebooks/class7-regex-with-song-lyrics-inclass.ipynb), [complete notebook](./notebooks/class7-regex-with-song-lyrics-complete.ipynb))

### Unit 2: Operationalizing Text as Data

9/24 – Sentiment analysis (a preview of what is to come)

* Before class:
	* Read: Ethan Reed, “[Measured Unrest in the Poetry of the Black Arts Movement](https://scholarslab.lib.virginia.edu/blog/measured-unrest-in-the-poetry-of-the-black-arts-movement/)”
	* Read: Catherine D’Ignazio and Lauren Klein, “[The Numbers Don’t Speak for Themselves](https://bookbook.pubpub.org/pub/6ui5n4vo)”
* In class: Sentiment analysis of our song lyric corpus and, if time, discussion of context (song lyric corpus: [complete notebook](../notebooks/class8-lyrics-scraping-complete.ipynb) | sentiment analysis: [class notebook](../notebooks/class8-sentiment-analysis-inclass.ipynb), [complete notebook](../notebooks/class8-sentiment-analysis-complete.ipynb))

9/26 – Intro to Colored Conventions Project Corpus 

* Before class:
	* Read: P. Gabrielle Foreman, Sarah Patterson, and Jim Casey, “[Introduction to the Colored Conventions Movement](http://coloredconventions.org/introduction-to-movement)” and “[CCP Principles](http://coloredconventions.org/ccp-principles)”
	* Watch: “[The Colored Conventions Project in Three Videos](http://coloredconventions.org/project-videos)” (watch the three videos)

* In class: Skype with Colored Conventions Project Team and Unit 1 Survey

10/1 – Topic modeling

* Before class:
	* Read: Cameron Blevins, “[Topic Modeling Martha Ballard’s Diary](http://www.cameronblevins.org/posts/topic-modeling-martha-ballards-diary/)”
	* Read: Lisa Rhody, “[Topic Modeling and Figurative Language](http://journalofdigitalhumanities.org/2-1/topic-modeling-and-figurative-language-by-lisa-m-rhody/)”
	
* In class: topic modeling ([class notebook](../notebooks/class9/class9-topic-modeling-inclass.ipynb), [complete notebook](../notebooks/class9-topic-modeling-complete.ipynb)) 	

10/3 – Word counts, tf-idf

* **HW 2 Due:** Sentiment analysis of the Colored Conventions Corpus

* Before class:
	* Read: Charlie Smart, “[The Differences in How CNN, MSNBC, & Fox Cover the News](https://pudding.cool/2018/01/chyrons/)”
	
* In class: word counts, tf-idf ([class notebook](../notebooks/class10-counting-words-inclass.ipynb), [complete notebook](../notebooks/class10-counting-words-complete.ipynb))

10/8 – More with word counts and tf-idf

* In class: more word counts and tf-idf

10/10 – Part-of-speech tagging and Named Entity Recognition 

* Before class:
	* Read: Lauren Klein, “[The Image of Absence: Archival Silence, Data Visualization, and James Hemings](https://read-dukeupress-edu.proxy.library.emory.edu/american-literature/article-pdf/85/4/661/393292/AL854_03Klein_Fpp.pdf)”
	* Read: Ishan Misra et al., “[Seeing through the Human Reporting Bias: Visual Classifiers from Noisy Human-Centric Labels](https://arxiv.org/pdf/1512.06974.pdf?fbclid=IwAR2OwfGEBmPR2ngyN0Hu2JYIEa7rwUe2VTGV8x3laDp89KxL1o6LBERXb9M)”

* In class: POS tagging, NER ([class notebook](../notebooks/class11-nlp-spacy-inclass.ipynb), [complete notebook](../notebooks/class11-nlp-spacy-complete.ipynb))

<div align="center"> 	
	<b>[ FALL BREAK ]</b>
</div>

10/17 – Word vectors 

* Before class:
	* Read: Sarah Connell, “[Word Embedding Models are the New Topic Models](https://web.northeastern.edu/nulab/word-embedding-model/)”
	* Read: Ben Schmidt, “[Gendered Language in Teacher Reviews](http://benschmidt.org/profGender)”
* In class: word vectors ([class notebook](../notebooks/class12-word-vectors-inclass.ipynb), [complete notebook](../notebooks/class12-word-vectors-complete.ipynb))

* **HW 3 Due:** CCP analysis 

### Unit 3: (More) Modeling Textual Data

10/22 – Pandas (finally!) / intro of final project 

* Read: Heather Krasue, “[Data Biographies: Getting to Know Your Data](https://gijn.org/2017/03/27/data-biographies-getting-to-know-your-data/)”
* Read: Timnit Gebru et al., “[Datasheets for Datasets](https://arxiv.org/pdf/1803.09010.pdf)”

* In class: pandas ([class notebook](../notebooks/class13-pandas-inclass.ipynb), [complete notebook](../notebooks/class13-pandas-complete.ipynb))

10/24 – More pandas / more final project

* In class: more pandas ([class notebook](../notebooks/class14-pandas-in-action-inclass.ipynb), [complete notebook](../notebooks/class14-pandas-in-action-complete.ipynb))

10/29 – Classification

* Read: Patrick Juola, “[How a Computer Program Helped Show J.K. Rowling Wrote A Cuckoo’s Calling](https://www.scientificamerican.com/article/how-a-computer-program-helped-show-jk-rowling-write-a-cuckoos-calling/)” (and [more technical version](https://languagelog.ldc.upenn.edu/nll/?p=5315) if you're curious)
* Read: Terra Blevins et al., “[Automatically Processing Tweets from Gang-Involved Youth: Towards Detecting Loss and Aggression](https://www.aclweb.org/anthology/C16-1207)”

* In class: classification ([class notebook](../notebooks/class15-classification-inclass.ipynb), [complete notebook](../notebooks/class15-classification-complete.ipynb))

* **FPP 1 Due: Datasheet OR Project Proposal**

10/31 – Clustering

* Read: Matt Daniels, “[The Language of Hip Hop](https://pudding.cool/2017/09/hip-hop-words/)”
* Read: Alexis Madrigal, “[How Netflix Reverse Engineered Hollywood](https://www.theatlantic.com/technology/archive/2014/01/how-netflix-reverse-engineered-hollywood/282679/)”

* In class: classification ([class notebook and required files](../notebooks/class16.zip), [complete notebook](../notebooks/class16/class16-clustering-complete.ipynb))

11/5 – Bits and bobs

* In class: more classification ([class notebook](../notebooks/class17-more-classifying-inclass.ipynb) and more clustering ([class notebook](../notebooks/class17-more-clustering-inclass.ipynb))

11/7 – NO CLASS, Professor at conference

* **FPP 2 Due: Datasheet OR Project Proposal**

### Unit 4: Arguing with Textual Data

11/12 – Making arguments, day 1

* Read: Dong Nguyen et al., “[How we do things with words: Analyzing text as social and cultural data](https://arxiv.org/pdf/1907.01468.pdf)”

* In class: discussion of Nguyen paper and final project

11/14 – Making arguments, day 2

* Read: Hoyt Long and Richard Jean So, “[Literary Pattern Recognition: Modernism between Close Reading and Machine Learning](https://www-journals-uchicago-edu.proxy.library.emory.edu/doi/pdfplus/10.1086/684353)”
* Read: Eshwar Chandrasekharan et al., "[You Can’t Stay Here: The Efficacy of Reddit’s 2015 Ban Examined Through Hate Speech](http://comp.social.gatech.edu/papers/cscw18-chand-hate.pdf)"

* In class: discussion of assigned papers (and a few other examples) ([class slides](../slides/class18-slides.pdf))

11/19 – Validation day 1

* Read: Matthew Salganik, “Moving Beyond Simple Experiments,” from Bit by Bit: Social Research in the Digital Age (on Canvas)

* In class: overview of methods of validation ([class slides](../slides/class19-slides.pdf))

11/21 – Validation day 2

* Read: Richard Jean So, “[All Models are Wrong](https://www-mlajournals-org.proxy.library.emory.edu/doi/pdf/10.1632/pmla.2017.132.3.668)”
* Read: Safiya Noble, “Introduction” and “Searching for Black Girls” from Algorithms of Oppression: How Search Engines Reinforce Racism (on Canvas)

* In class: discussion of idea of validation 

* **FPP 3 Due: Exploratory Analysis**

11/26 – NO CLASS, Thanksgiving

<div align="center"> 	
	<b>[ THANKSGIVING BREAK ]</b>
</div>

12/3 – Project presentations

12/5 – Project presentations

12/10 – Course wrap-up and assessment

### FINAL PROJECTS DUE DECEMBER 17TH, 5:30PM

*This syllabus has been inspired by the courses of [Jinho Choi](https://github.com/emory-courses/data-science), [Alison Parrish](http://www.decontextualize.com/teaching/), [David Mimno](https://mimno.infosci.cornell.edu/info3350/), [David Bamman](http://people.ischool.berkeley.edu/~dbamman/info256.html), [Ryan Cordell](http://s17hda.ryancordell.org), and [Ben Schmidt](http://benschmidt.org/HDA19/), as well as suggestions and other input from Heather Froehlich, Ted Underwood, Jacob Eisenstein, Jim Casey, Taylor Arnold, Lauren Tilton, Lisa Rhody, Eileen Clancy, and the Colored Conventions Project Team.*
