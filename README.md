# COVID-19 Remote Education Starter Kit

This solution starter was created by technologists from IBM.

## Authors

- [Derek Teay](https://developer.ibm.com/profiles/derek.teay/) - IBM
- [John Walicki](https://developer.ibm.com/profiles/walicki/) - IBM
- [Pedro Cruz](https://developer.ibm.com/profiles/pedro.cruz/) - IBM
- [Spencer Krum](https://developer.ibm.com/profiles/skrum/) - IBM
- [Daniel Cunnington](https://developer.ibm.com/profiles/dancunnington/) - IBM
- [Kevin Allen](https://developer.ibm.com/profiles/kallen/) - IBM
- [Neil MacKinnon](https://developer.ibm.com/profiles/neilmack/) - IBM
- [Armen Pischdotchian](https://developer.ibm.com/profiles/apischdo/) - IBM
- Phaedra Boinodiris - IBM

## Contents

1. [Overview](#overview)
1. [The idea](#the-idea)
1. [The architecture](#the-architecture)
1. [Prerequisite](#prerequisite)
1. [Tutorials](#tutorials)
1. [Technology](#technology)
1. [Documents](#documents)
1. [License](#license)

## Overview

### What's the problem?
Part of the World Health Organization's guidance on limiting further spread of COVID-19 is to practice social distancing. As a result, schools in most affected areas are taking precautionary measures by closing their facilities. With school-aged children at home for an indeterminate amount of time,  keeping them engaged, entertained, and on top of their education is important. 

### How can technology help?
Schools and teachers can continue to engage with their students through virtual classrooms, and even create interactive spaces for classes. As parents face a new situation where they may need to homeschool their children, finding appropriate online resources is important as well. 

## The idea
It's imperative that learning and creating can continue when educational institutions have to shift the way they teach in times of crises, such as the COVID-19 pandemic. Providing a set of open source tools, backed by IBM Cloud and Watson Services, will enable educators to more easily make content available for their students.

## The architecture

### Quiz App
![Quiz app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-quiz-app-example/images/cfc-covid19-remote-education-diagram-1.png)

1. The user navigates to the site.
2. The user is presented with a website, a React front end.

  3a. The user performs an action within the Express app.

  3b. The LoopBack-generated code performs the necessary task within the Express app.

4. Changes are saved in a PluggableDB.

### Video transcription/translation app
![Video transcription/translation app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## Prerequisite
- Register for an [IBM Cloud](https://www.ibm.com/account/reg/us-en/signup?formid=urx-42793&eventid=cfc-2020?cm_mmc=OSocial_Blog-_-Audience+Developer_Developer+Conversation-_-WW_WW-_-cfc-2020-ghub-starterkit-education_ov75914&cm_mmca1=000039JL&cm_mmca2=10008917) account. 

## Tutorials
Following are a set of resources developers can build on to enhance remote education during times of social distancing. This starter kit includes three components: 

- [Create a quiz app to assess online learning](https://developer.ibm.com/tutorials/cfc-starter-kit-quiz-app-example/)
  - Learn how to build a simple example quiz application that uses a Loopback-generated express app with a React front end.
- [Build a video transcriber service](https://developer.ibm.com/tutorials/cfc-starter-kit-speech-to-text-app-example/)
  - Learn how to create a sample Python app that can extract text from instructional videos using Watson Speech to Text. This functionality will allow instructors to provide notes to students who are using video and audio tools as their primary way to learn. 
- [Set up a Skills Network platform](https://developer.ibm.com/tutorials/cfc-starter-kit-skills-network-implementation/)
  - Learn how to build a highly configurable, robust virtual classroom environment for instructors that enables course development, virtual assistant help, live classrooms, and more.

## Technology
- IBM Technology
  - [Node.js Express App](https://developer.ibm.com/technologies/node-js/)
  - [Cloud Object Storage](https://www.ibm.com/cloud/object-storage)
  - [Cloud Foundry](https://www.ibm.com/cloud/cloud-foundry)
  - [IBM Cloud Kubernetes Service](https://www.ibm.com/cloud/container-service/)
  - [Watson Speech to Text](https://www.ibm.com/cloud/watson-speech-to-text)
  - [Watson Language Translator](https://www.ibm.com/watson/services/language-translator/)
- Open source technologies
  - [Python](https://www.python.org/)
  - [Docker](https://www.docker.com/)
  - [Vue.js](https://vuejs.org/)
  - [React](https://reactjs.org/)
  - [LoopBack](https://loopback.io/)
  - [Swagger](https://swagger.io/)

## Documents
- [Starter Kit page](https://developer.ibm.com/callforcode/getstarted/covid-19/remote-education/)
- [Kubernetes](https://www.ibm.com/cloud/learn/kubernetes)
- [Docker](https://www.ibm.com/cloud/learn/docker)
- [Cloud Object Storage](https://www.ibm.com/cloud/learn/object-storage)
- [Containerization](https://www.ibm.com/cloud/learn/containerization)
- [Official IBM Speech to Text demo](https://speech-to-text-demo.ng.bluemix.net/)
- [Official IBM Language Translator demo](https://language-translator-demo.ng.bluemix.net/)

## License
This solution starter is made available under the [Apache 2 License](LICENSE).
