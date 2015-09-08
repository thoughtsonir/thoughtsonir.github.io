---
layout: article
title:  Comments on ICML 2015
date:   2015-07-18 
categories: [machinelearning]
image:
    teaser: icml.png
author: sira_ferradans
---

I went to [ICML][icml15] last week, and it was clear that deep learning is still creating a huge hype. Althought, there was a very interesting warning in a plenary talk:  

<blockquote>
<p><em>We are using data as proxies for concepts</em></p>
<p><cite>Léon Bottou (Facebook AI, Research), <em>Two high stakes challenges in machine learning</em></cite></p>
</blockquote>

Deep learning algorithms use a huge amount of data to train on the detection of elements of a certain 'category'. For instance, in computer vision, a neural network is feed with thousands of images of a cars, in different situations, so the system can detect a car in a new image that it has not seen before. An interesting example he showed, was a car in a non-typical situation: inside a swimming pool. In this case, the system failed to recognize it. Of course, this may be a very important situation to detect in order to warn, for instance, the police. This failure was most probably due to the fact that the images that were used in the training set, didn't show this situation, there were not enough examples for the system to learn that a car might be in a swimming pool, after all. 


Another very interesting aspect was the final panel discussion. All the participants were very much into the deep learning research community, so I missed dissonant opinions. Anyway, a question that somebody in the audience posed, and had a very interesting answer, was if we should be afraid of this new artificial intelligence that we do not understand. The answer was very simiar from all of them "no". I believe that they are completely right. We are teaching now machines to make sentences from a picture, a 2 year old kid can do this. What should be worrying us is the following: 

<ul>
<li>how humans are going to be dealing with all this new information. Information is power, as we have seen in the news lately (Snowden case, for instance), and humans are good at abusing power, thus a very thorough analysis should be done. 
</li>
<li>The data analysis community should not make the population have to decided between participating in the world vs. giving all my data to internet entities. The machine learning community should develop tools to allow anonimity on the internet.
</li>
</ul>




[icml15]:      http://icml.cc/2015/
