---
layout: post
title:  "Delijaj's report"
date:   2019-01-16 16:17:00 +0100
categories: reports
author: Delijaj
---

# Report of Delijaj Sofia

## Introduction
In the idea of our course *Open Science*, we needed to do a project related to the SDGs by having it as an open access project.
We chose to participate in the project of _Thomas Maillart_ because, with the help of discussion Nyomi had with him by mail, we found it really interesting and a great opportunity to learn new concepts (later on Bileg joined us and helped a lot with the design and coding). The project is about making a trading market. We want to put some _"Gamification"_ in it, which means we want to put a reward for each contribution you make and the reward is some tokens. The tokens will be used to buy some project's parts or you can get some by selling the parts you own.
The report will mostly be about my experience throughout the project (struggling mostly) and its process.

## Problem statement
This project concerns every SDG issues, in other words, the purpose is to get every project related to any SDG. The idea is to find contributors and investors to make any SDG project grow and promote them as well (some small projects can get recognized and become a bigger adventure).

## Methodology
I mostly worked with Github, Plot.ly and D3.js.
#### GitHub
GitHub is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code. I knew what it was but never really worked with it, I was excited to finally be able to use it and learn more about it. I actually had many issues with it. At first the repositories were a mystery, the fork system wasn't that clear, the markdown language was new for me (and it was even the first time I heard about it). With the help of internet and Xoeseko, I can now better understand the functionalities (even if I still have issues using Git).
#### Jekyll
Jekyll is a simple, blog-aware, static site generator for personal or organization sites. We used it in making the documentation website. This was mostly used by Nyomi and Bileg, although I installed it and tested it with our documentation page. I don't really recommend it for that fact that launching the website locally can be tricky (I couldn't, for some reasons which is still unknown, download some "gems" for our site).
#### Plot.ly and D3
Both are library used to generate dynamic visualizations in Javascript and to use them on a website (with HTML). The Plot.ly library is complete and useful making lots kind of charts and visualizations. There are some examples on how we can do the charts and some useful documentations.

In the end, because we have open science, I could find answers to my questions and tools to help me and my group the tolls to go forward and learn.

## Research Results & Solution Proposal
### The meeting
After several mails we needed to meet Mr.Maillart to see what we could do to help the project without giving us too much to be able to follow the
other courses/projects we had. As the website was relatively new, we had many different tasks which are the ones below:

>1. tester l'interface & API sous toutes ses coutures
=> poster des issues, dialoguer avec les développeurs
=> documenter votre pratique de l'open source avec l'approche critique dans le cadre debugging / onboarding
=> peut-être installer et utiliser Jupyter notebook sur un github repo qui est lui même sur le sdg.market
=> documenter l'experience "recursive" (=> créer un github repo pour étudier le sdg.market, lequel repo est lui-même sur sdg.market)
>=> voir : https://mybinder.org/
=> voir : https://github.com/binder-examples
>2. construire des visualisations de protofolios et/ou d'évolution des cours des projets / series de temps de génération de tokens
=> http://blockbuilder.org/
=> d3.js + gallery
>3. Eventuellement faire quelques statistiques
=> envoyer extended abstract
=> slides
>4. Reflexion générale critique mais constructive.
=> check & balances entre ce que propose le white paper & le prototype son potentiel de dévloppement
>5. Reflexion sur comment on pourrait faire une implémentation blockchain
>6. github page
=> jekyll

He said that we didn't have to do all of them, but we took is as a challenge.
Afterwards, we made our repository in GitHub and created the issues on Nyomi's repository. We assigned some tasks and started to do it.
### Checks and Balances
I needed to review the whitepaper to see what has been done and if they managed to do what the whitepaper said. Looking at the state of the website, basic, we could imagine that it is easy. However, as there are so little information displayed (more when you are an admin) and even with testing all the options this task was harder than I assumed. At the beginning I believed that I needed to do a kind of review of it but I was wrong and had to redo it (with Nyomi this time).
### Visualization
At the beginning, I wanted to make a big chart with multiple coloured lines which you can select to choose what information you want to see displayed. But with my lack of knowledge concerning the JavaScript language and the time I had to do it, I decided to make a linear and more simplistic one. On the website, we can select the chart at a certain time do screenshots.
The JavaScript language was hard to understand at some points since it's very different from the languages I know, I searched in many websites, such as Stack overflow to find answers (even finding what didn't work was difficult enough).
With the poor amount of data we had, I tried, with the help of my team, to make some visualizations to have a better view of what is happening. I wanted to do a dynamic visualization that allows you to see what is happening over time. The idea in the end is to put it available to the users, like a view of your performances. This view can allow also for the future investors, thus you can look at the productivity or the effectiveness of a contributor.  
## Future Plans
As expected, we couldn't do all issues, only the blockchain implementation remains. However we do want to try and finish it after the exams (or even get more involved with the project itself since we have few ideas and questions that we will ask Maillart when meet).
When the website has advanced, we could test some other ideas from the whitepaper and mostly how they will use and generate the tokens (mentionned in Bayar's report).

## Documentation
- https://sdg-market.oniabsis.com/
- https://xoeseko.github.io/sdg.market/whitepaper/
- https://xoeseko.github.io/sdg.market/data%20visualisations/dynamicVisu
- https://github.com/Xoeseko/sdg.market/issues
- https://xoeseko.github.io/sdg.market/reports/2018/11/30/Bayar-journey
- https://xoeseko.github.io/sdg.market/reports/2018/12/29/xoeseko-journey
