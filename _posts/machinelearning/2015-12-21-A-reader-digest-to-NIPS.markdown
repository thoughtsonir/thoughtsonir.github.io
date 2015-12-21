---
layout: article
title:  A reader's digest to NIPS 2015
date:   2015-12-21
categories: [machinelearning]
image:
    teaser: NIPS.png
author: mathieu_andreux
---
I attended [NIPS][nips] two weeks ago, as it took place in Montréal from the 7th to the 12th of December.
It was huge: according to the chairs, the number of attendees rose by 40% in one year, leading to about 3500 people.
Yet, it did not feel crowded, thanks to the very effective organization of Montréal's Palais des congrès. 

<img src="/images/nips15_attendance.png"/>

Deep learning was the key point at this conference: although only 10% of papers were primarily concerned by deep learning, a lot of optimization and Bayesian optimization papers were related to deep learning in some way or another.
As Zoubin Gharamani pointed out, the field is in a situation analogous to the one which prevailed 25 years ago, in the early 90s: neural networks were flourishing, a lot of efforts were devoted to training them, SVM were only being invented. 
In between, we have obtained a better understanding of what statistical learning means.
Instead of finding the best architecture to do stuff, I think it's high time we understand what "deep" learning means before going any further in this direction.

<h2>Some interesting papers</h2>

Here are some papers that I found interesting at this conference. I tried to group them by categories, although some of them could be attached to multiple categories:

<ul>
<li>
Phase retrieval:
<li>
[Solving Random Quadratic Systems of Equations is Nearly as Easy as Solving Linear Systems][phase1]
</li>
<li>
[Efficient Compressive Phase Retrieval with Constrained Sensing Vectors][https://papers.nips.cc/paper/6021-efficient-compressive-phase-retrieval-with-constrained-sensing-vectors]
</li>
</li>
</ul>

<h2>The future of AI</h2>
It appears that AI is once again a [hype][neil_lawrence_hype] keyword.
In some aspects, it actually looks like we're in a science-fiction movie.
This topic was discussed at the Symposium "Brains, Minds and Machines", which was chaired by Tomaso Poggio.

In particular, Joshua Tenenbaum presented a [recent work][] done in collaboration with deep learning people, which was pretty impressive. They developed a hierarchical generative model aimed at zero-shot learning. When presented a single instance of a foreign character, the computer is able to reproduce and recognize multiple examples of this character, with performances quite comparable to humans. Tenenbaum insisted on the forecoming meeting of cognitive reasoning with deep learning perception, and I think he might be right.

At the end of NIPS, the [OpenAI][openai] initiative was announced. Funded by private donors (notably Elon Musk and Peter Thiel), it will be an open research lab focused on AI technology. I think it's a very nice initiative, and another indicator of how hot the field is (the pledges involve around $1B). Let's see what it gives!


[nips]: http://nips.cc/
[neil_lawrence_hype]: http://inverseprobability.com/2015/12/13/hype/
[openai]: https://openai.com
[phase1]: https://papers.nips.cc/paper/5743-solving-random-quadratic-systems-of-equations-is-nearly-as-easy-as-solving-linear-systems
