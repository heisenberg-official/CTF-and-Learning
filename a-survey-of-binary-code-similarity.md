---
description: 'https://arxiv.org/pdf/1909.11424.pdf - Authors : Ifran Ul Haq, Juan Caballero'
---

# A Survey of Binary Code Similarity

Understanding what people have done in the past is important because it's not just help you save your time but also expanding your knowledges about the research area, gaining information about the previous problems to know which problems are still left-over and to know if there is still room left for improvements on a working method. 

> Over the past 20 years numerous binary code similarity approaches have been proposed, but the research area has not yet been systematically analyzed.

To give the reader a big-picture view of Binary Code Similarity, author have done a great job of systematizing 61 approaches by 5 characteristics. It's also worth noting that there is not only 61 approaches through 20 years of researching, but these 61 approaches are quite distinctive to others. A deep explaination of these characteristics could be found in **VI** so I will not go any deeper, if you are curious, take a look at the original paper.

> For example, the approach systematization includes, among others, the number of input pieces of binary code being compared \(e.g., one-to-one, one-to-many, many-to-many\); the granularity of the pieces of binary code analyzed \(e.g., basic blocks, functions, programs\); whether the comparison happens at the syntactical representation, the graph structure, or the code semantics; the type of analysis used \(e.g., static, dynamic, symbolic\), and the techniques used for scalability \(e.g., hashing, embedding, indexing\).

They also differentiate these approaches by its application. For people who care more about applications, you can take a look at chapter **IV**, where author talks about different application of Binary Code Similarity with link to multiple approaches for that application or just look at the below table.  That would be great starting point for people who just get into the field or just care about one or few applications of Binary Code Similarity. 

![](.gitbook/assets/image%20%28260%29.png)

But due to my personal interests, I care more about the history of this research area. It's amazing to know that the need of Binary Code Similarity is actually came from the need of updating binary in low bandwith communication networks and the limited resources in some devices

> The increasing popularity of low bandwidth communication networks \(e.g., wireless\) and the limited resources in some devices, raised interest in techniques that would increase efficiency by transmitting a small patch that captured the differences between two versions of a binary, i.e., non-text, file, instead of transmitting the whole fil

> In 1991, Reichenberger proposed a diffing technique for generating patches between arbitrary binary files without any knowledge about the file structure

Many others approaches have developed later on with the expansion of the scope from one-to-one to many-to-many and one-to-many.  But only until 2004,  the re-ordering problem was solved by Thomas Dullien with the introduction of the Small Primes Product algorithm
