# Artificial Images: StyleGAN2 Deep Dive

# Overview

[Artificial Images: StyleGAN2 Deep Dive](https://bustbright.square.site/product/machine-learning-class-stylegan/286) is a course for image makers (graphic designers, artists, illustrators and photographer) to learn about StyleGAN2. In this course you will learn about the history of GANs, the basics of StyleGAN and advanced features to get the most out of any StyleGAN2 model. Advanced topics will include training non-square models, mixing datasets, modifying training commands and a number of interpolation methods (image projection, vector manipulation, etc). 

Class meets on Sundays Apr 12 - May 10, at 12:30pm - 2pm EDT (1.5 hour sessions).

Taught by [Derrick Schultz](https://twitter.com/dvsch?lang=en) and TA [Lia Coleman](https://twitter.com/Lialialiacole).

## Course Syllabus

- **Week 1:** History of GANs, Inspiration, Environment Setup
- **Week 2:** StyleGAN Training Basics
- **Week 3**: StyleGAN Manipulation: Interpolation, Projection, Truncation
- **Week 4**: Advanced StyleGAN Techniques
- **Week 5:** Next Steps: Project Feedback, Your Own GPU Setup, Open Q&A

# Week 1, April 12

To-do before this class:
1. Set up your Google Cloud Platform (GCP) server. This is what we will be using in class for GPUs. Here are [instructions on how to set up GCP](https://www.youtube.com/watch?v=CBPJh33T3yQ). Expect this to take 30 minutes in one sitting. Don’t worry, this is the longest task in this list, everything else should be a breeze!
2. Bookmark this page!
3. Fill out the [pre-class survey](https://drive.google.com/open?id=1VYk7B0Chd534rVvE_1c4FTsRNk_ftWkB4qo2TPmM1X4).
4. Join our [Slack](https://ml-images.slack.com/) and poke around! For our class, we will be communicating through the `#stylegan2-deepdive` channel.
5. Introduce yourself to your classmates in the `#stylegan2-deepdive` channel. Say hi to each other! Some starter questions: Where are you located? What do you do? What experience do you have already? What do you want to learn or make? And links to your IG / twitter / website. :)
6. Read our class [Code of Conduct and Zoom Guidelines](https://docs.google.com/document/d/1Q6X4_uEdlx3Xo9ZM73nlltc690DcP4geSjImUEA7K98/edit?usp=sharing).


### Class Materials

- [Week 1 Slides](https://drive.google.com/open?id=1PkmZMbNHE29WgTiS__LkSHr8pIn56-baOWs3QPnktOo)
- [First Half of Week 2 Video](https://drive.google.com/open?id=1TXUjXuoXJJkzOeX-CUnN-XYsDDW8FfmT)
- Second Half presentations, re-recorded (because Derrick is an idiot)
  - [What is a GAN?](https://youtu.be/e1Ed3LGQpiA)
  - [A Brief History of GANs](https://youtu.be/0d2WsXtQHR8)
  - [StyleGAN2 Inspiration](https://youtu.be/lYoIn1aL37s)
- [Week 1 Notes](https://www.notion.so/Setup-History-of-GANs-Inspiration-0cd4ebe5d70a45589c6ca2267dee64a3)

### Homework
- Install StyleGAN2 libraries on GCP using [these instructions](https://github.com/dvschultz/ai/blob/master/StyleGAN-GCP.md)
- Start to build your dataset. Check out the [dataset-tools playlist on YouTube](https://www.youtube.com/watch?v=faS0pmd71fk&list=PLWuCzxqIpJs9v81cWpRC7nm94eTMtohHq) for help.

### Notes from class
- Robert Luxemburg’s [StyleGAN2 audio reactive video](https://twitter.com/robertluxemburg/status/1216442061060300800)
- [My remix of Bruce Conner’s _Breakaway_](https://www.instagram.com/p/B9Zu04zB--Y/)
- [Len Lye remix](https://www.youtube.com/watch?v=LQfM-cEY_TI&t=4s)

# Week 2, April 19
### Class Materials
- [Week 2 Slides](https://docs.google.com/presentation/d/1seAR2IpmHEElKu1Ve8fIZxNsoGRIjwcdTI7LVbvJZPw/edit?usp=sharing)
- [Week 2 Video](https://drive.google.com/open?id=1stZdMOWHXendJ7fbDDX-RKnD3hzV3TOX)
- [Week 2 Notes](https://www.notion.so/Training-StyleGAN2-abf6f824186b4920ae70b83ea362a724)

### Homework
- Finish your dataset.
- Start training your model! Follow this [video](https://www.youtube.com/watch?v=Ij1dqSVR89M) to train in GCP.

### Notes from class
- Kishi Yuma’s [hand piece](https://www.instagram.com/p/B0A8pOzDfvU/)
- Golan Levin, [_Augmented Hand Series_](http://www.flong.com/projects/augmented-hand-series/)
- [First Order Motion](https://aliaksandrsiarohin.github.io/first-order-model-website/)
- [Splitting a video into frames using ffmpeg](https://stackoverflow.com/questions/10957412/fastest-way-to-extract-frames-using-ffmpeg#answer-54442867) (I‘ll record a video this week)
- [Open Questions about Generative Adversarial Networks](https://distill.pub/2019/gan-open-problems/)
- [StyleGAN2 Projection in RunwayML](https://open-app.runwayml.com/?model=brunovianna/Stylegan2-projector) (will get to a full demo this week)

# Week 3, April 26
### Class Materials
- [Week 3 Slides](https://docs.google.com/presentation/d/1KwIDeSW8KF9dXpRzHMy1380NXrztxxDlp12J7osldtg/edit?usp=sharing)
- [Week 3 Video](https://drive.google.com/open?id=1aA-UOG3D_919DW_a6QXYVMfM5S80I8L5)
- [Week 3 Notes](https://www.notion.so/StyleGAN-Manipulation-fbbabb84c82f42beb8691feede44fec4)
- [StyleGAN2 Manipulation Colab Notebook](https://colab.research.google.com/drive/1_LIu91bFGCeeLPnuT8A669BYbtz0nwFI)

### Homework
- Finish Training!
- Make an animation!
    - Generate some images.
    - Animate truncation on your favorite image.
    - Interpolate between multiple images.
    - Try to find an image in your model using projection.

### Notes from class
- Justin Pinkney's [Awesome Pretrained StyleGAN models](https://github.com/justinpinkney/awesome-pretrained-stylegan2)
- Another StyleGAN2 notebook from [Mikael Christensen](https://colab.research.google.com/drive/1ShgW6wohEFQtqs_znMna3dzrcVoABKIH)
- A bunch of [ML Art Colab Notebooks](https://github.com/dvschultz/ml-art-colabs)

# Week 4, May 3
### Class Materials
- [Week 4 Slides](https://docs.google.com/presentation/d/1UH26sCqahjHDcJm_PS4VLsg0az_JWOx3hyPHQFKdWqk/edit?usp=sharing)
- Week 4 Video
- [Week 4 Notes](https://www.notion.so/Advanced-StyleGAN-Techniques-Projection-Audio-Reactive-262124e696914e64a4d8963dc475940e)
- [Colab Notebook with Projection and Near Neighbors](https://colab.research.google.com/drive/1_LIu91bFGCeeLPnuT8A669BYbtz0nwFI)
- [Colab Notebook for Audio Reaction](https://colab.research.google.com/drive/1fPbpOp6Nb2IPm-5V_Hn_Bfw1wHDQ79gz#scrollTo=1wlpnO6wftSp)

### Homework
- Keep working on your projects and manipulating your models in Colab.
- Schedule a 1:1 with us!

### Notes from class

# Week 5, May 10
