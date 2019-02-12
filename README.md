# NLP project using text data from university-wide survey 
## On learning another language 

A few years ago I was on a Task Force determing whether or not Rutgers should put in place a second-language requirement. The project entailed a large university-wide survey (N = 35,000), which has since then turned into a new study, "Rutgers Multilingual Survey". In light of practicing some interesting NLP technologies, I tried out some word co-occurences and LDA models to do some exploratory analyses on the data. 

First were the columns pertaining to students' attitude toward taking another language

<p align="center">
  <img src="images/Reasons to NOT take a language.png">
</p>

After, I then looked at those same students and why they would NOT take another language. 
<p align="center">
  <img src="images/Reasons to take a language.png">
</p>

I'll expand on this later. But I combined all the text to construct a Laten Dirchlet Allocation (LDA) model on these data. The algorithm doesn't choose the number of topics for you. So I arbitrarily set k at 8, 16, 24, and 32. At a first glance, looks like I'd need to take out some stop-words. 

<p align="center">
  <img src="images/Top 10 terms in each LDA topic(k = 8).png">
</p>

<p align="center">
  <img src="images/Top 10 terms in each LDA topic(k = 16).png">
</p>


<p align="center">
  <img src="images/Top 10 terms in each LDA topic(k = 24).png">
</p>
