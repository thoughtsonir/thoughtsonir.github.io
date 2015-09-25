---
layout: article
title:  Comments on ICML 2015
date:   2015-07-18 
categories: [machinelearning]
image:
    teaser: icml.png
author: sira_ferradans
---
I went to [ICML][icml15] last week, and it was clear that deep learning is still creating a huge hype. There were several high level discussions that I found specially interesting. 

<h2>Data and Objects</h2>

There was a very interesting warning in a plenary talk about our treatment of data and learning:  

<blockquote>
<p><em>We are using data as proxies for concepts</em></p>
<p><cite>Léon Bottou (Facebook AI, Research), <em>Two high stakes challenges in machine learning</em></cite></p>
</blockquote>

This sentence is clear that summarizes the core belief of deep learning methods. Deep learning algorithms use a huge amount of data to train algorithms to the detect elements of a certain 'category'. For instance, in computer vision, a neural network is fed with thousands of images of cars, in different situations, so the system can detect a car in a new image that it has not seen before. An interesting example he showed, was a car in a non-typical situation: inside a swimming pool. In this case, the system failed to recognize it. 
 This result makes a very interesting point. The issue is that, in general, the input images follow a pattern that exemplifies the common situation where you will see a car: on the road. Of course, being a car is related to the 'road' concept, but the road is not a part of the car, and the system should be able to distinguish between the two concepts, even if they are linked. We may say that this is a very uncommon situation, and that it is not that relevant in every-day life. The thing is that, this 'uncommon' situation may be of great importance for security applications, for instance in this case, you may want to be calling an ambulance or the police.

<hr />

<h2>Challenges on security and anonimity</h2>

Another very interesting aspect was the final panel discussion. All the participants were very much into the deep learning research community, so I missed dissonant opinions. Anyway, a question that somebody in the audience posed, and had a very interesting answer, was if we should be afraid of this new artificial intelligence that we do not understand. The answer was very similar from all of them: 'No'. I believe that they are completely right. We are teaching now machines to create sentences that summarize the scene of a picture. You can see here some examples extracted from this [paper][captiongeneration]: 

 <img src="/images/captiongeneration.jpg" />

Although their results are very good, the whole task does not look very threatening to humans from an intelligence point of view. Instead, what should be worrying us is the following: 

<ul>
<li>How humans are going to be dealing with all this new information. Information is power, as we have seen in the news lately (Snowden case, for instance), and humans are good at abusing power, as history has taught us. So, we should be having an open discussion on how this power can be controlled. More specifically, I think an important topic is the ownership of the data people generate, and how it should be treated. This goes from personal information you post on the web, to statistical information you are giving when interacting with the tools on the web. 
</li>
<li>Linked to the previous point, the data analysis community has an important role to be played. Althought science has no ideology, technology does. The creation of knowledge is important, but what you do with it is even more. The data scientists are responsibles for the tools that are being created on this area, and therefore responsible for what can be done with the knowledge of data analysis. Therefore, we should not make the population have to decide between participating in the world and giving all my data to internet entities, and the void. The machine learning community needs to develop tools to allow anonimity on the internet, so that particiting on the internet community doesn't mean stop having privacy. 
</li>
</ul>




[icml15]:      http://icml.cc/2015/
[captiongeneration]: http://jmlr.org/proceedings/papers/v37/xuc15.pdf
