Blog 2: **Manifest(o) Destiny**

In this post, I explore text analysis using AntConc through Elliot Rodger’s manifesto, “My Twisted World.” I've chosen this exercise as a way to think about the sociological use of computational text analysis methods, even for researchers who are not well-versed in these techniques (such as myself). Looking at as basic an aspect of text analysis as word concordance is, of course, necessarily a preliminary and exploratory form of analysis that I mean to use here for primarily theoretical and/or speculative purposes.

Elliot Rodger was, in short, a domestic terrorist. On May 24, 2014, as a response to his lifelong experience of being denied sexual access to women, Rodger killed 6 people and injured 14 others in Isla Vista, CA<sup>1</sup>. Afterward, he turned his gun on himself. The Rodger manifesto, "My Twisted World," is 137 pages long in its PDF form and is largely autobiographical. In it, Rodger recounts his life story in sometimes excruciating detail, with particular attention to his feelings about women, other men, and sexuality. At various times, particularly toward the end, these memories are intertwined with Rodger's plans for his "Day of Retribution." I was able to obtain the Rodger manifesto through traditional online channels, found and accessed through Google search. After I downloaded it as a PDF file, I used Google Docs to convert it to plain text, which I uploaded to AntConc. AntConc is an easy-to-use text analysis toolkit designed for learning by Laurence Anthony. It can be downloaded for free [here](https://www.laurenceanthony.net/software/antconc/).

The first term I chose to search for was "kill*." Morbid, yes, but appropriate in the given context. The asterisk functions as a wildcard placeholder that ensures AntConc will return all terms based on the root term "kill." AntConc returned 45 results.

One of the first things I noticed was the number of times Rodger says he "had" or "would have" to kill compared to the number of times he says he "wants" or "wanted" to kill. While any analysis of this is entirely speculative, there are some interesting things to consider here. The tendency toward describing killing as something that is imperative, rather than a personal choice could have implications for the ["red pill" type] ideology espoused by Rodger (and those who have come to venerate him, after his martyrdom for the incel cause). Looking for and/or measuring expressions of violence as a duty associated wth particular social and/or political beliefs could be a dimension of research that attempts to predict when online extremists will make good on threats, for example.

![kill concordance](killconcordance.png)
<font size="1">Here are displayed results for "kill" with no *, in order to include both "had/have" and "want/ed" in the screenshot. There were no other forms of "kill" that were accompanied by these terms, so nothing relevant is lost in this condensation.</font>

Next, I looked at the concordance plot for "kill*." The concordance plot is a bar visualization of the length of the text, with incidences of the search term marked on the bar at the point in the text at which they appear. Interestingly, it seems that Rodger's use of the word kill first just after the middle of the text and increases in use as he approaches the end. This likely reflects the autobiographical tone of "My Twisted World," as his vengeful fantasies only begin to emerge around the time of adolescence and sexual discovery. More... 

![kill concordance plot](killconcordanceplot.png)
<font size="1">Concordance plot for "kill*"</font>

The second term I chose to search was "sex*." Given that Rodger's extremist worldview revolved around sexual access to women (or rather, his lack thereof), it is easy to imagine that this is a significant term in the text. AntConc returned 190 results.
 
Something that struck me as I looked through these results was the block pictured in the screenshot below, particularly where "sex and love" are repeatedly paired together.
 
 
 
![sex concordance](sexandloveconcordance.png)
<font size="1">Selected concordance results for "sex*"</font>





























<sup>1</sup>Duke, Alan. “Timeline to ‘Retribution’: Isla Vista attacks planned over years.” CNN. May 27, 2014. Retrieved from https://www.cnn.com/2014/05/26/justice/california-elliot-rodger-timeline/index.html 