---
layout: article
title:  McGurk Effect and multimodal learning
date:   2015-09-22 
categories: [signalprocessing]
image:
    teaser: men_talking.jpeg
author: sira_ferradans
---

How merging different kinds of information can help us with classical signal processing tasks. 

Our brain merges different sources of information to get a better understanding of the world, in a way that is transparent to us. This merging process has not been successfully achieved yet by automatic methods. An example of this the source separation problem in signal processing which is still challenging in many contexts. This problem consists in the following: given a recording with different sounds at the same time, we want to separate automatically all the independent sources. What is surprising is that humans can do this effortlesslly. A very common situation is the party context. We are at a party with many people talking and with a lot of background noise. But, when we engage in a conversation with a single person we can understand them well mainly because we are able to separate their voice from the background sound. It is well known that in this case, the brain is not only using the information obtained from the sound, but also the visual information, in this case the motion of the lips. 

Another example of this is when listening to an orchestra. If you close your eyes while listening, it is difficult to isolate the sound of a single instrument, but if we focus our visual attention on it, it becomes much easier. 

In both cases, the brain uses the visual information given by the motion of elements producing the sound (lips or instrument), together with the auditive information to better understand the person that is speaking or the instrument that is playing. So, the perception of the sound gets enhaced by the spatio/temporal information. But how deep is this change? can the spatio/temporal information modify what we hear?

When studying the behaviour of the brain, the illusions always give us an insight of what is going on. In our case, we have the '[McGurk Effect][McGurkEffect]'. This illusion shows that in some cases the brain can change the perception of the audio in order to make it match the visual information. For instance, when looking at somebody talking, the sound that we understand has to be in accordance with motion of the lips that we see. If not, our brain will make a decision and choose one of the two possible perceptions: visual information or the sound information. 

In this video, you can see a nice example that shows that our brain 'hears' what it sees. The authors took two videos, one of a person saying 'ba' and another saying 'va'. Then, they put the sound of the first recording to both videos. The effect is clear, the sound perception is different even if the sounds are exactly the same:

<iframe width="656" height="369" src="https://www.youtube.com/embed/G-lN8vWm3m0" frameborder="0" allowfullscreen></iframe>



<hr />

<h2>Multimodal Learning</h2>

The idea of merging information from different sources to solve a signal processing problem has gained track in the last few years. The main challenge is how to fuse the information coming from different sources. We can think of two  problems that show the challenge from different perspectives. The first one is how to identify the person that is talking from a audiovisual recording. In this case, the interest is locate the source of sound but we don't actually care about the content. This problem is normally posed when trying to analyze the interaction between people in a room, for instance. The second one is language transcription from a video of the person's face. Here, the main interest is the actual content of the sound, and how the video (motion of the lips) can enhance the identification of the words in the sound recording.

Audio and image/video have complementary information. Audio is temporally very precise (for audio recordings we have 44100 samples per second), but it is spatially non-located. Video, instead, is temporally very imprecise (24 frames per second), but the objects of interest are well defined spatially. How to handle the information that is so different is the challenging task.

An interesting approach given by [Deleforge et al.][Deleforge] is to pose the problem as 'how to do audio-to-image translation'. If we can convert the audio signal into a 2D signal and map it onto the image, the fusion problem is solved. In this paper, they propose to map spatially the sound as a spatial mark, equal for any kind of sound


[McGurkEffect]: http://www.nature.com/nature/journal/v264/n5588/abs/264746a0.html

[Deleforge]:https://hal.archives-ouvertes.fr/hal-01019287/document