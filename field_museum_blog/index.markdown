---
title: "Field Museum Blog"
category: field_museum_blog
layout: addit_pages_layout
---

This past week I started my internship at the Field Museum in downtown Chicago. Two years ago, the summer after my junior year of high school, I did the Digital Learning Internship at the Field Museum where I collaborated with five other high school students to create a game, Seeds for Survival, in the museum's Plant Hall. This summer, I'll be working with Dr. Matt von Konrat and his team studying bryophytes in the Botany Department with some machine learning projects.

In this first week, I mostly helped reorganize the specimen collection. I've never seen so many different types of plants in one place ever, and honestly it's a bit overwhelming. Towards the end, I sat down with Matt and we talked about my project for the summer which is essentially broken down into three parts:

**1. Data Analysis with Microplants**

An ongoing project right now uses a Zooniverse project on microplants (really <i>really</i> small plants measured in microns (10e-6 meters)). The project can be done on a computer or a kiosk, and it gives the user a picture of part of a microplant under a microscope and the user uses their mouse or finger to measure out the length and width of the leaves. Although the task doesn't seem mind blowing, the project's advocacy of citizen science expedites the data collection process for scientists, and the data is then used to help determine speciation of various microplants. My role here will be to work with another undergraduate student to devise a way to convert the pixel measurements Zooniverse takes into microns and to create a Python script to clean the data to be usable.

**2. Plant Measurements with Morphosnake**

The second part of the project utilizes Morphosnake, a software for plant image analysis which takes in a skeletonized image of a plant then takes measurements of each branch, outputting the statistical summary. These measurements again will be used to distinguish various species that may be similar. The department has been struggling to get the software up and running, so that's step 1. After that, we want to look into having a script to automate to process of skeletonizing the images.

**3. Machine Learning to Automate the Species Determination**

The last part of the project is what I'm most excited for! There was a paper published from the Smithsonian that used a convolutional neural network (CNN) to classify two families of of specimen that look very similar to each other. We want to be able to accomplish this with our specimen collection at the Field Musuem, so the first step is almost trying to replicate the steps they took and then being able to apply a similar model on different family/specimen/etc. This will be a really good way for me to get some experience in machine learning and hopefully understand what's happening as well, not just mimicking the steps.

I'm genuinely really excited for this summer! I love the idea of applying computer science into a field that hasn't really been exposed to it yet and seeing how much of an impact technology will be able to make. In addition to working at the Field Museum, I'll also be collaborating with CS professors and graduate students from North Eastern Illinois University (NEIU) for guidance! (which we all know I'll need a lot of)