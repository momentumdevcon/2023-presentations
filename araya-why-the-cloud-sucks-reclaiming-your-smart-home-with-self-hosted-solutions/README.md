# Why the Cloud Sucks - Reclaiming your smart home with self-hosted solutions

Arturo Araya &mdash; *Arturo Araya, Lead Software Engineer, Fifth Third Bank*

- [LinkedIn](https://www.linkedin.com/in/arturoarayacincinnati/)

## Bio

Arturo has had dual, sometimes competing, sometimes collaborating, passions in both music and technology since he was 10. After pursuing, and receiving, a Bachelors, Masters, and  finally an Artist Diploma in Cello Performance from  Oberlin Conservatory and the University of Cincinnati's College-Conservatory of Music, and after then briefly performing as principal cellist of the Shenzhen Symphony Orchestra in Shenzhen, PRC, Arturo's career took him in a completely different direction. 

Currently, Arturo is tech lead for Fifth Third Bank in the areas of Software Security and Risk Mitigation, where he gets to cooperate with great people, solving interesting puzzles that  make the online banking experience safer for all of Fifth Third's customers. While he still pursues music, off the clock Arturo works on crafting his own smart home system, building components from scratch, and working out how to get them to talk to one another. He spends equal amounts of time tending to his home lab, a sort of "digital garden".

## Abstract

It’s been a long day. For hours it seems like there’s been nothing but work crises to deal with, but finally, you’re home. As you approach your driveway you tell your phone to open the garage door, ... but nothing happens. It’s happened again: the cloud service controlling your garage door is on the fritz. Now you have to try to find what you were hoping would become a quaint artifact of a bygone era, the garage door opener. Luckily, this isn’t your first rodeo, so you fish it out of its hidden place behind a nearby planter. The automation that normally recognizes you from presence detection software running on that same cloud service also fails, so you fish for your keys to the back door. It’s raining, and it’s cold. And now you’re not sure you remembered to bring your keys after all. You longingly think back to the promise of home automation, when you thought you wouldn’t have to fumble for keys, or garage door openers ever again. You reflect on your predicament, and wonder how it could have all gone so terribly wrong.

If you’ve ever dabbled in smart homes or home automation you’re probably been there. The truth is home automation these days is almost synonymous with the cloud. Wander down any home improvement store, or run any Google search, and the vast majority of smart home offerings are underpinned by varied, and often conflicting, cloud services and standards. Sure, “Works with Alexa” is helpful, and the ease of just plugging it in, setting up some credentials, and configuring automations is extremely seductive, but what happens if Alexa, or rather AWS, goes down in your area? Or more prosaically, what if your internet goes down?

A better solution can be found in self-hosting your smart home. It takes more time, effort, and maintenance, but what you lose in instant gratification, you gain in knowing exactly what makes everything tick, and in the knowledge that if it goes down you know what to do. In this talk, I will present what building a self-hosted smart home entails, both the good and the bad. I will cover overall design decisions you will have to make and how to plan your process, including answering the all-important question, “how do I find smart home products that are cloud independent”?. I will also cover how to connect your devices to locally-running APIs, and how to bring it all together in one central panel. I will end by discussing three essential smart home items, and how to engineer them yourself in a way your whole family will feel confident using them. 
1. Garage door opener
2. LED smart light
3. Central, open-source, control center

While this won’t be a coding session, code will be discussed, even shown. Join me as we discuss the true smart home of the future; the self-hosted smart home.


- **Level**: Intermediate
- **Tags**: Design, Hardware & IoT, Back-End, Other
  