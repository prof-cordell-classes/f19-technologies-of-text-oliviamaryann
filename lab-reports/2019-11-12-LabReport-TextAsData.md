#Lab Report: Text as Data
####Olivia Mastrosimone 
##Process Description 
In this lab, we worked with code to learn more about text. I had a lot of trouble with this lab as I have learned I am code-illiterate, so bear with my elementary descriptions! We began by opening up R studio, which is a coding language and platform, and entering into an R markdown document, which blends code and markdown to integrate prose into code. We began the actual coding with simple math and messages, which was the last thing I felt confident doing. After doing addition and coding the message "Hello World," we brought in the concept of packages, which are "collections of functions, data, and documentation that extend the capabilities of base R." We downloaded tidyverse and tidytext, and then began talking about variables. 

Here's where I lost most comprehension in what I was doing, but I know I did it, so I'll try and describe it. We explored variables using Barton's *Scenes from a Cerical Life*. I ran the code View(barton) and was given the world's worst spreadsheet, ran the code barton$text and got a large block of text filled with \n's and \r's, and then

barton$text <- gsub("\r\n", " ", barton$text) 

barton$text

and got the same text but with line breaks. My understanding is that that we were manipulating the variable to change the way we see the data. 

Then, we moved to working with Jane Austen and project Gutenberg. First, we loaded the Gutenbergr package, which we used to import Project Gutenberg data in a cleaner dataframe. We first imported Austen's collection of work, and used increasingly more specific code to give increasingly more specific outputs – word count, word frequency, word frequency exclusing stopwords, and then these criteria applied to specific books. We also produced graphs that went from very unhelpful to *almost* helpful, and were able to begin to gather meaningful information from the words Austen used. 

##Observations 
What was I confused about or frustrated by during this lab? Where do I begin. I have always prided myself in my ability to understand computers and technology generally. But this lab absolutely destroyed any confidence I have in just, kind of *getting* code. In fact, it made me realize I can not comprehend this abstractly. It is an odd experience working with something in which the fundamental idea makes absolutely no sense. I simply do not know how code works, and how me typing in back ticks or brackets can produce any output. I guess it's a good time for an existential crisis, because if coding is the future, then I am *very* behind. 

However, this lab wasn't all crisis inducing, and did pleasantly surprise me at times. Generally, the ability to combine text and code this fluidly is not something I had really thought possible or necessary. I never gave any thought to how coding could be useful in analyzing texts, or why. I had a moment of cliched awe when I realized the extent of computing power. As someone who is very far removed from this world, this lab allowed me to peek into the enormity of computer science and (kind of) understand how it can be used in the humanities. 

##Analysis
It was this last observation that I really got stuck on while doing this lab. There are new analyses and conclusions just waiting to be drawn from text that are only reachable through code, and the meaning of a text is no longer beholden to its form *as* text. Here's a quote from *The Thrilling Adventures of Lovelace and Babbage* that touches on what I'm getting at: 

	Liberated from the static shell of the materoal, transliterated 
	to the purely symbological, sublimated into a state entirely 
	new! It can be filed, indexed, converted, replicated, searched, 
	shared, shuffled, linked, remixed, recombined, archived, 
	analyticated, resurrected!
	
Here, Ada Lovelace is referenced the new, and unwilling, translation of George Elliot's manuscript into code. While reading this, I felt it was a bit silly, and that coded textual information couldn't have that many possibilities for analysis. But, after completing this lab, my mind was completely changed. Using code to explore literature opens up a whole different world of textual analysis – one that goes further than just reading. Plugging in a simple string of code and gathering information about word frequency in Austen's entire body of work is something students and scholars simply could not do until very recently. This lab made me feel quite proud to be studying English in the advent of this new form of literary studies, even if I don't really get it. 

But, being that coded analysis is still relavtively new, and requries certain technology to do, I also found myself shocked with the exclusivity of it, both physically and ideologically. George Elliot was unable to comprehend why her manuscript was shredded and turned into little dots punched into paper, unable to phathom how that could be of more literary importance than her book. To be honest, I found myself, at times during this lab, thinking the same thing. What group of people has access to this method of analysis? What group of people is this analysis benefitting? I tend to think these two groups overlap greatly. 

I don't mean to completely write off the practice and significance of using code to explore literature, but I do wonder how it can be presented to and used by a wider audience. If coding is on track to be the next generation of childrens' second language, then using it in English classes should be commonplace. 