# NLP project using text data from large survey 
## On learning another language 

A quick exploratory look at word co-occurences from large survey. 

First were the columns pertaining to students' attitude toward taking another language
<p align="center">
  <img src="images/Reasons to take a language.png">
</p>


After, I then looked at those same students and why they would NOT take another language. 


<p align="center">
  <img src="images/Reasons to NOT take a language.png">
</p>A




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
