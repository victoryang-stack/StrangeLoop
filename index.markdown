---
layout: single_page
---

{% assign media = site.mindoc_media | where: "page", "source" | sort: "order" %}


# Introduction

{% include media_next.html pages=media %}

Strange Loop Gazette lies at the intersection of philosophy and artificial intelligence as it stood in the 1970s. It is a brilliant insight into a unique intellectual environment. Three men were involved in this document: Scott Kim, Martin Gardner, and Douglas Hofstadter. Douglas Hofstadter wrote the nonfiction philosophical work Gödel, Escher, Bach: An Eternal Golden Braid. Scott Kim wrote the Strange Loop Gazette, which summarized Hofstadter’s work. And Kim sent the Gazette to Martin Gardner, a columnist of Scientific American magazine whose review of Gödel, Escher, Bach catapulted Hofstadter to a Pulitzer Prize. This document is at the center of that story, providing key insight into technological dreamings of the late 1970s. It was the Strange Loop Gazette that introduced Gardner to Gödel, Escher, Bach, and today it has become more relevant than ever and just as effective.

This edition is meant to get the message of Gödel, Escher, Bach out to a modern-day audience. In a world engulfed by artificial intelligence, the content of GEB and the Strange Loop Gazette has become more important than ever. With this edition, one will develop a friendship with a forgotten era of artificial intelligence: that of the imaginative. The vehicle of these ideas is the Strange Loop Gazette. In one way, this edition is meant to give a new perspective on Gödel, Escher, Bach for new readers; in another, it is meant to introduce new readers to these contents. That is best accomplished with the Gazette. 
  
The copy of the Strange Loop Gazette seen here was discovered in the Stanford University Archives by Glen Layne-Worthey and scanned by him. A special thank you goes to him for his help in this edition and in providing the source material to us.
  
Included in this edition is a transcription of the document, annotated for modern readers and supplemented with scans of the original. Also included are in-depth descriptions of this document and its context for the curious. The edition is also peppered with images to convey some of the more difficult philosophical concepts. Presented here is a new Gödel, Escher, Bach care package. Below begins your adventure.

**How to Cite:**

Schultz, Julia, Alex Von Holten, Ewan Ward, and Yang, Victor. "Strange Loop.". December 7th, 2025. https://victoryang-stack.github.io/StrangeLoop/.

# The Source

*(Anything **bolded** was underlined by Gardner on the manuscript; anything* italicized *was circled by Gardner on the manuscript)*


STRANGE LOOP GAZETTE

The official Gödel Escher Bach fan newsletter.

volume 1, number 2[^1]

November 16, 1978[^2]
Scott Kim
Box 9414
Stanford, CA 94305

Martin Gardner
10 Euclid Avenue
Hastings-on-Hudson
New York 10706

Dear Martin,

Here I am, much to my surprise, back at Stanford, this time in the guise of a computer science graduate student. I’m currently listed as a Master’s student, but will certainly have to switch to PhD in order to do research. It would have been nice to have gone to another school (I may still), but I’ve by no means exhausted the possibilities here. I’ll probably work on computer graphics/music, with the goal of creating a computer graphics setup for extending my visualization skills (towards mathematical, artistic, or other ends). Then there is always the danger that I will run off and become an animator.

Doug Hofstadter is now putting the final touches on his “Gödel Escher Bach” manuscript. He decided to do **all the typesetting and illustrating himself.[^3]** There are some 50 drawn illustrations, and perhaps 600 pages of text, so this is no mean feat. But he (and I) find considerable satisfaction in “handcrafting” the book, following it through its entire production. After all, the layout and choice of typestyle makes an enormous aesthetic difference. Besides, if his publisher is relieved of most production costs, the book can probably be sold for a much lower price.

Incidentally, typesetting the book means taking the manuscript, which is already in computer readable form, inserting special symbols which describe which typefaces to use and various spacing information, and feeding it all to a special photo-typesetting machine. This has the amusing aspect that his manuscript must first be muddied up with all manner of editorial remark (in this case directed towards the photo-typesetting machine) before it can emerge in its final pure form. In this case the final form is long rolls of 8 1/2 inch-wide photographic paper, which Basic Books will cut and paste into book-shaped pages.

Seeing that the publisher Basic Books is planning to release GEB soon (March 1979), I thought that I should write to urge you to devote a column to the book. GEB is enormously important to me (I feel quite privileged to have watched the book develop), and I want to do everything I can to help it reach its audience.

Doug informs me that you do not currently have a copy of the manuscript. Basic will send you one soon I’m sure, but even with the manuscript, the sheer size, makes it difficult to sort out material appropriate for your column. So here are what I consider some of the highlights. (Note: there is more to this letter, but in the interest of timeliness, I’m sending you as much as I have done. More to come later.)[^4]

{% include media_next.html pages=media %}
  
##### (transcription of section 7, magic, and section 8, structural puns)

7: Magic

An analogy which Doug doesn’t use: “AI is magic”. True, but most people don’t understand magic. Magicians use all sorts of perpetual tricks to guide beliefs. Unless one is acquainted with this power, it all does seem “like magic”. In AI, formal rules are used to model informal systems. Unless one is acquainted with the power of formal systems, the thought of artificial intelligence seems “magical”. GEB gives the reader insight into the power of formal languages, and thus indicates the road to demystifying intelligence. Of course saying that intelligence might have a mechanical basis does not make it any less magical, someone who knows how the tricks are done does not make it any less magical; someone who knows how the tricks are done is only that much more appreciative of the illusionist’s skill.

A specific misdirection technique which appears prominently in GEB is the idea of framing. For instance, the best way to convince an audience that there is nothing “tricky” going on is to create a small doubt, then dispel it. The doubt sets the frame of expectations. The audience will expect no more tricks once the doubt is resolved. Framing devices are often used in advertisement to convince you that claims are genuine.

Finally, GEB abounds with **“magical” coincidences.** For instance, it hardly seems possible that the *Goldbach* **conjecture and the Goldberg Variations were proposed/composed in the same year.** How could Doug have **predicted such serendipity?** The answer of course is that he didn’t. The source material for GEB is so rich that such **coincidences could hardly** be avoided. Once Doug made some curious observation, previous passages were rewritten to make the connection seem preordained. This is known in magic circles as **_“goal switching”.[^5]_** Again, knowing how it’s done does not in any way detract from the enjoyment.

{% include media_next.html pages=media %}
  
8: Structural puns
  
GEB is constructed around two complementary ideas: “structural puns” and “jumping out of the system”. “Structural pun” is a term I am coining to describe what Doug does in his dialogues; “jumping out of the system” is an all-purpose escape from structural tangles.

Puns are based on the possibility that a single word may have two different meanings. Normally the two meanings are “at the same level” though they may be in different classes – “bare skin” and “bear skin” both refer to things out in the real world, even though “bare” is an adjective and “bear” is a noun being used as an adjective.

In a “structural” pun, at least one meaning refers not to the world out there, but to some aspect of language itself. Examples:
  
  (1)	This page intentionally left blank.
  
  (2)	I’m the world’s most modest person.
  
  (3)	?tfel ot thgir morf gnidaer uoy era yhW
  
  (4)	This sentence no verb.[^6]
  
  (5)	What do I do if I run into a problem?
  If you have any problems, just ask.
  
  (6)	Gebstadter, Egbert B. Copper, Silver, Gold: an Indestructible Metallic Alloy. Perth: Acidic Books, 1979.

A formidable hodge-podge, turgid and confused–yet similar in spirit to the present work. Contains some excellent examples of indirect-self-reference. Of particular interest is a reference in its well-**annotated bibliography** to **an isomorphic, but imaginary, book.**

In all cases, the form, the phrasing of the sentence, interacts with its content. Example (1) actually appears (especially in government documents), which makes it all the funnier. Example (2) is irony of a form which often appears in comedy. Example (3) is a rather smart-aleck remark, which, unlike the previous two examples, does not rely on paradox for its humor. Example (4) is not paradoxical either, but requires some quite subtle analysis on the part of the reader. (This sentence appears as an example in the chapter entitled “Self-ref and self-rep”.) Example (5) requires a previous sentence to set the context in which the statement is made. Example (6) requires the most elaborate context of all–the whole of GEB. This description appears in the bibliography of GEB, and requires (among other things) that the reader be looking for tricky acronyms.

Structural puns are used throughout the dialogues of GEB to multiply illustrate certain patterns of thought useful in discussing logic and intelligence. For instance, the dialogue “Sonata for Unaccompanied Achilles” illustrates the idea of figure and ground through both its form (on end of a telephone conversation) and its content (an analysis of an interlocking Escher print). This dual approach enriches the texture of the illustration, with the implicit irony **that Achilles does not notice** the **double meanings of his solo.** Here Doug is borrowing a technique from music–theme and variation.

The continued use of form/content reverberation also sets up the important notion of indirect self-reference–in discussing Eschers’ figures and grounds, Achilles is implicitly and only implicitly talking about the structure of his phone conversation. Indirect self-reference figures strongly in the proof of Gödel’s incompleteness theorem.

Structural puns have occurred before in the literature; GEB goes further in the depth and consistency to which the idea is applied. **The whole book is itself a _“strange loop”_,[^7]** as explained in “Overall form”. Finally, the concept of “structural pun” is being used in two different senses: as a form in which to write dialogues, and as an illustration of indirect self-reference. This double meaning is in turn another structural pun, which means there are structural puns on three levels, which means there are structural puns on four levels, which means…

(I think.) ((I think.)) (((I think.))) ((((I think.)))) 

{% include media_next.html pages=media %}
{% include media_next.html pages=media %}

# About this Source

The Strange Loop Gazette written by Scott Kim in 1978 offers a rare behind-the-scenes look at the intellectual environment present during the publication of *Gödel, Escher, Bach* (GEB). Unlike GEB, Strange Loop was not written for a general audience, but for someone with intellectual experience on the subjects covered in the book and a familiarity with their shared sense of humor- specifically columnist of Mathematical Games at *Scientific American* magazine, Martin Gardner.[^8] Because of this, it is difficult to introduce any new readers through this letter alone. While its insights are very special and holds an interesting historical significance, the writing is arguably too dense. With this in mind, our annotated edition strives toward accessibility and attempts to remedy this gap in understanding by providing crucial background knowledge that the original letter might assume. Through its appreciation of GEB and the topics it covers, especially self-reference and formal systems, it showcases a moment from before it exploded into popularity, and from the perspective of a fellow puzzler and mathematician.

This particular copy of the *Strange Loop Gazette* is one of two known and was discovered in the Stanford Archives by Glen Layne-Worthey, who now works in the School of Information Sciences at the University of Illinois. He created the document scans seen previously. It is unclear how that copy came into the possession of the Stanford Archives.

### Section 1: Intellectual Network of Strange Loop

While Strange Loop was individually written by Scott Kim, the letter was also heavily influenced by the minds of both Douglas Hofstadter and Martin Gardner, all three of which sharing an interest in mathematics, statistics, and general logic, but each having a distinct direction, all combined in structuring Strange Loop.

Douglas Hofstadter, being the author of GEB, provides a lot of the conceptual backbone to the three’s roles in developing Strange Loop. His interests in self-reference, recreational mathematics, cognitive psychology, etc. all shape how Kim would write Strange Loop and its respective commentary. While it’s obvious that Hofstadter would influence the document written about his book, the fact that Scott Kim influenced GEB himself isn’t. During the later years of writing GEB and while they were both colleagues, Kim’s ‘playful’ writing style had inspired Hofstadter to add more wordplay into the book, using ‘structured puns’ and puzzles as a way to communicate ideas about self-reference.[^9]

As for Martin Gardner, through his decades-long work in Mathematical Games, he inspired and would continue to inspire many to pursue mathematics non-traditionally and as a form of recreation, notably puzzles.[^10] While Hofstadter and Kim were both big fans of Gardner, Kim was already very open about it and knew Gardner before he knew Hofstadter and worked on GEB. This connection allowed for him to write Strange Loop as a letter to Gardner, which led to Gardner reviewing GEB in his column. Hofstadter credits this column for GEB’s following popularity.[^11] Not only shaping Hofstadter’s interest in puzzles and mind-games, he’d also indirectly influenced him through Kim, who’d largely taken up interest in puzzle designing because of Gardner. 

### Section 2: Formal Systems and Gardner’s Legacy

Kim’s use of puzzles is important to understanding the historical context and relevance of Strange Loop and the edition in general. Kim writes based on GEB, so it becomes paramount to understnad the relationship between Kim's visuals and Hofstadter's writing. Kim’s work is deeply rooted in the systems and illustrations highlighted by Douglas Hofstadter. Kim weaves the puzzles Hofstadter illuminates in his own writing. Kim isn’t just offering brainteazers or puzzles, he is adding his understanding to the mathematical space and philosophical inquiries that Martin Gardner popularized.[^12]

Recognizing the influential work in mathematics spurred on by Gardner is also key to understanding *Strange Loop*, GEB, and Kim’s interest in this space. Recognizing the work that Gardner has put into these thoughts helps readers appreciate why Strange Loop matters. *Strange Loop* is the intersection of mathematics, logic, philosophy, art, and history; it carries ideas that have shaped how scholars and general audiences think about problem-solving skills and structured thought. This has become evident when examining the fanbase that surrounds Strange Loop and the respective literature and influences.[^13] The fanbase is living proof of the legacy that Gardner has left with his intellectual community that has been further fleshed out by individuals like Kim through writing like Strange Loop. 

### Section 3: Self-Reference and “Strange Loops”

The theme of self-reference is a very central one to not only GEB, but by proxy Strange Loop, acting as the foundation of both structures. Hofstadter firstly took inspiration for this idea from Kurt Gödel, a highly influential mathematician and logician, who created the Incompleteness theorem. “I am not provable,” as it is often shortened to, basically means that within any system, there will always be true statements that cannot be linearly proven. Kim highlights this idea throughout his text, using “structural puns”, mirrored sentences, and other forms of word play, along with an expansion on Hofstadter’s use of Escher’s paradoxical paintings and Bach’s looping musical structure. While they may not be immediately recognizable as self-referential, they do play a part in providing understanding of the theme. These three strands tie together the braid that is Gödel, Escher, Bach.[^14]
  
Kim hones in on Hofstadter’s concepts of “strange loops” as an extension of his theme of self-reference. Essentially, strange loops (sometimes referred to as ‘tangled hierarchies’ by Kim) are infinite, looping, self-referential structures that exist between many different levels of repetition but at the same time as one. This is represented through a number of ways in the texts, notably with the aforementioned Escher and Bach. Escher’s paintings are a visual representation of this idea. Two key examples include Drawing Hands, which depicts two hands drawing each other, and Ascending and Descending, which depicts a series of people walking up an infinite staircase looping into itself. As for Bach, his self-reference is musical, with his fugues climbing and restarting cyclically.
	
### Section 4: Early AI

Early developments in artificial intelligence also provide essential thematic context for understanding Strange Loop. The late 20th century saw individuals who were interested in AI (or researching the idea of AI) thinking through questions about how machines connect to human reasoning, creativity, and self-awareness.[^15] These questions can be linked back to Hofstadter’s work regarding self-referencing and strange loops themselves. In turn, these questions also resonate with Kim and his ideas presented in Strange Loop. Early AI systems rely on formal logic and structures; this mirrors the same structure as the puzzles and patterns Kim highlights in his writing. By viewing Strange Loop through the lens of early AI exploration, readers can have a deeper understanding of how the text has a deep historical context when applied to the idea of AI. The text reflects structural choices that are relevant to AI - like a loop being capable of examining itself. Importantly, Hofstadter sees the formal structures of artificial intelligence at this time as a source of self-reflection and of inspiration rather than as an intellectual shortcut.
	
### Conclusion / Why This Edition Is Necessary Today

Overall, Strange Loop is a very dense document, not having been intended for a general audience. Though while making it harder for new readers to connect with, it does well to engage with those who are already familiar with these concepts. Fans of GEB and the fields it touches on may be interested to learn of a new perspective from before the book was even published. By adding annotations and additional context to the document, it not only helps to familiarise readers with the concepts touched on in Strange Loop and by proxy GEB, but it also sparks an interest in those who may be intrigued with the ideas of GEB, but are ultimately discouraged either due to the length of the book or the complexity of the ideas it discusses.

# About this Edition

This edition presents an annotated transcription of Scott Kim’s Strange Loop, a document written about Douglas Hofstadter’s Gödel, Escher, Bach. Given its difficult accessibility and heavy assumption of background knowledge, our edition aims to address these concerns for new readers, while also supplying additional information for those already familiar with GEB. Specifically, we intend on publishing annotated transcripts of excerpts of Scott Kim’s Strange Loop, image files that support the information highlighted in Strange Loop, and our research helping to explain some of the key points that are developed in this prototype. This correspondence is difficult to find online, with the copy in our edition having been found in Stanford Archives, which is one of the reasons why we believe our prototype is so important. 

In the original text, there are several places where we opted to explain the context of the specific sentence/line/concept. These are footnotes that we have added on the transcription that we have created. Our transcriptions were written by hand based on the original correspondence that Kim wrote. While we currently don’t have the entirety of Strange Loop transcribed, we have included several excerpts that show the depth of Kim’s ideas that he engages with in the text. To allow for further accuracy in our edition, we’ve also added image scans of the original alongside our transcriptions, helping to clarify changes and annotations made.

# Supplements

Should you wish to include any supplemental materials--such as specific forms of source commentary or illustrations--they may be provided here.  They are not required. If you do not have any supplements, please eliminate this field.

# Bibliography

Abeles, Francine F. “Mathematics: Logic and Lewis Carroll.” Nature 527, no. 7578 (2015): 302–4. 111069800. https://doi.org/10.1038/527302a. 

Fandom. 2025. “Gödel, Escher, Bach Wiki.” Fandom.com. 2025. https://godel-escher-bach.fandom.com/wiki/G%C3%B6del.

Gaisman, Jonathan. “The Heart of the Fugue.” The New Criterion (UNITED STATES) 42, no. 9 (2024): 77–80. A2417001. https://research-ebsco-com.proxy2.library.illinois.edu/linkprocessor/plink?id=0a9bdc05-6b46-35d5-b973-4236689ff5a7
 
Game Thinking TV, dir. How AI Pioneer Doug Hofstadter Wrote Gödel, Escher, Bach. 2023. https://www.youtube.com/watch?v=JYZcHSqqxtg. 

Gardner, Martin. “Mathematical Games: The Inspired Geometrical Symmetries of Scott Kim.” Scientific American. Scientific American, Inc, 1981. doi:10.1038/scientificamerican0681-22.

Gardner, Martin. “Mathematical Games: Douglas R. Hofstadter’s “Godel, Escher, Bach.” Scientific American 241, no. 1 (1979): 16–28. http://www.jstor.org/stable/24965235.

Hofstadter, Douglas R. Godel, Escher, Bach: An eternal golden braid. New York: Basic Books, 1979. 

Infinite Negative Utility. 2018. “Why I Don’t Love Gödel, Escher, Bach.” Infinite Negative Utility. July 4, 2018. https://journal.infinitenegativeutility.com/why-i-dont-love-godel-escher-bach.

Masood, Adnan. 2025. “Hofstadter’s Gödel, Escher, Bach: An Eternal Golden Braid Review— Choosing an Operating Model Under….” Medium. August 20, 2025. https://medium.com/@adnanmasood/hofstadters-g%C3%B6del-escher-bach-an-eternal-golden-braid-choosing-an-operating-model-under-df35a183372e.

Mirsky, Steve. “Remembering Martin Gardner, with Douglas Hofstadter.” Scientific American, May 24, 2010. https://www.scientificamerican.com/podcast/episode/remembering-martin-gardner-with-dou-10-05-24/.

MIT. 2025. “MIT OpenCourseWare.” MIT OpenCourseWare. November 3, 2025. https://mitocw.zendesk.com/hc/en-us/articles/5332864282907-Highlights-for-High-School.

Mulcahy, Colm, and Dana Richards. “Let the Games Continue.” Scientific American 311, no. 4 (2014): 90–95. 98530162. https://doi.org/10.1038/scientificamerican1014-90. 

Newborn, M. (2011c). Beyond Deep blue: Chess in the Stratosphere. Springer Science & Business Media.

Peters, Michael A., et al. ‘AI and the Future of Humanity: ChatGPT-4, Philosophy and Education – Critical Responses’. Educational Philosophy and Theory, vol. 56, no. 9, July 2024

Somers, James. “The Man Who Would Teach Machines to Think. (Douglas Hofstadter).” The Atlantic Monthly. Boston: Atlantic Media, Ltd, Nov. 2013.

# Credits and Acknowledgments

Please thank your clients, as well as anyone else you would like to thank for their assistance in making this edition.

# Optional: Author Biography

If you wish to include short bios of yourselves as authors, please put them here.  This is optional.

# About MinDoc 1.0
_Please leave this credit (eliminating this italicized part)_

> This site was built using MinDoc 1.0, a prototype digital documentary edition template developed for classroom use by members of [SourceLab](https://sourcelab.history.illinois.edu/) at the University of Illinois Urbana-Champaign.  The original project team included Liza Senatrova, John Randolph, Caroline Kness, and Richard Young.

# References

[^1]: This is probably a joke. Gardner and Kim certainly would've found this kind of wordplay funny.
[^2]: This date is about three months before the book's official publication and release.
[^3]: This was a remarkable achievement in the 1970s and a huge undertaking to typeset and illustrate an entire book yourself. Gardner also wrote a circled "!" in the margins.
[^4]: At least one other copy of the "Gazette" exists, but it is unclear if Kim ever did write more summary.
[^5]: Gardner wrote the circled word "outs" in the margin, with a line pointing to this term.
[^6]: This pun opens Gardner's column on *Gödel, Escher, Bach,* in his *Scientific American* column.
[^7]: This was an intellectual wellspring for Hofstadter, who would later expand on this idea in his 2007 book *I Am a Strange Loop.*
[^8]: Gardner, “Mathematical Games.”
[^9]: Game Thinking TV, How AI Pioneer Doug Hofstadter Wrote Gödel, Escher, Bach.
[^10]: Mulcahy and Richards, "Let the Games Continue," pp. 1-2.
[^11]: Game Thinking TV, How AI Pioneer Doug Hofstadter Wrote Gödel, Escher, Bach; Mirsky, "Remembering Martin Gardner with Douglas Hofstadter."
[^12]: Gardner, “Mathematical Games.”
[^13]: Fandom, “Gödel, Escher, Bach Wiki.” 
[^14]: Game Thinking TV, How AI Pioneer Doug Hofstadter Wrote Gödel, Escher, Bach.
[^15]: Peters, et al. “AI and the Future of Humanity.”
