---
layout: project
type: project
image: images/COVIDKokuaFinancialSquare.png
title: COVID Kokua
permalink: projects/covid-kokua
# All dates must be YYYY-MM-DD format!
date: 2020-12-17
labels:
  - Javascript
  - COVID
summary: A website designed to help users navigate the resources available to them regarding the COVID-19 pandemic.
---

<img class="ui meduim rounded image" src="../images/COVIDKokuaLanding.png">

COVID-Kokua, titled Kokua-Hawaii on our website due to domain name acquisition issues, is a series of tools designed to help people living in Hawai'i navigate the various COVID-19 related resources that exist. It was developed as the final project for a software engineering class. A team of four, including myself, were responsible for the website's creation. More information about the website and a user guide can be found at: [https://covid-kokua.github.io/](https://covid-kokua.github.io/). I was responsible for both the `Financial Information` page and the `FAQ` page. All featured information was synthesized on the web, filtered by us, and added to the section most relevant. In addition to financial information, the website provides various information specific to students, related to getting food assistance or COVID-19 helplines. This website was designed to better sort the available resources so that they may be accessed in a helpful way.

<img class="ui meduim rounded image" src="../images/COVIDKokuaFinancial.png">

The `Financial Information` page was designed for usability, so that users of the website could contribute new resources if they appeared. We may not have the time or the knowledge to update the website with every new resource that is created, so providing an avenue for a user to fill in gaps in the resources is important to keeping an up-to-date list of available resources. This page loads resources from a `Mongo` collection, and adding new resources adds them to this collection. In this, if a user adds to a live website, that resource is available for anyone else viewing the site.

<img class="ui meduim rounded image" src="../images/COVIDKokuaFAQ.png">

The FAQ page is relatively barebones, but does contain useful information. We did not receive enough feedback concerned with the usability of the website to create a suite of questions regarding confusing aspects of the site.