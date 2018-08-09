---
layout: page
title: Projects
permalink: /projects/
---

### Data Aggregation Server for IOT (DASI)
#### Jul 2017 - Sep 2017

Designing and developing a dynamic data aggregation server using Python (Flask).
The server can gather data in different formats from many devices (e.g. sensors) and these informations can be accessed in a standard format through HTTP endpoints.
The server can be configured using a file specifying the way in which data from device can be parsed.
Users can set alarms for abnormal measurement and can block endpoints for devices sending invalid or unwanted data.
The technology stack is the following:
- Python Flask;
- JWT;
- MongoDB;
- Redis;
- Docker.

The project was developed together with [Mario Villani](https://github.com/MarioVillani).

***

### [Voto col Portafoglio](https://itunes.apple.com/it/app/voto-col-portafoglio/id1244405835?mt=8) 
#### Apr 2017 - Aug 2017

I developed front-end for Voto col Portafoglio app: a cross-platform mobile application developed with React Native, using Native Base as UI Framework.

The project was developed together with [Mario Villani](https://github.com/MarioVillani) and [Vincenzo Tavarone](https://github.com/VincenzoTavarone).

***

### [Giffoni Social Experience](https://play.google.com/store/apps/details?id=com.ionicframework.gffapp387189&hl=en) 
#### May 2016 - Jul 2016
I developed backend for Giffoni Social Experience 2017. In depth, I did:
 - Data scraping from Giffoni Film Festival Web site;
 - Designing and developing Giffoni Social Experience app's backend with Node.js and MongoDB;
 - Designing and developing Giffoni Social Experience app's CMS using Bootstrap, PHP and jQuery.

The project was developed together with [Mario Villani](https://github.com/MarioVillani) and [Vincenzo Tavarone](https://github.com/VincenzoTavarone).

***

### [NJOY Campania](https://play.google.com/store/apps/details?id=it.njoy.campania)
#### Feb 2016 - Apr 2016
I designed and developed backend for NJOY Campania using MondoDB as database and Node.js (Express as framework) for the server.

The project was developed together with [Mario Villani](https://github.com/MarioVillani).

***

## University Projects


### [prefix-search](https://github.com/dariodip/prefix-search)
#### Apr 2018 - Jul 2018

prefix-search is an implementation of the algorithm introduced in the [paper](https://link.springer.com/chapter/10.1007/978-3-642-40450-4_40) *Compressed Cache-Oblivious String B-tree* of Paolo Ferragina and Rossano Venturini. 
We developed the proposed algorithm (LPRC) and a new one (PSRC), giving you the ability to deal with online dictionaries of strings in an unspecified order.
The project was developed using [Go](https://golang.org/) for the core of the algorithm and Python for the random test generator and the analysis of the results. 
We also used [Travis CI](https://travis-ci.org/) for Continuous Integration, in order to test our project at each new commit and pull request.

The project was developed together with [Mattia Tomeo](https://github.com/mattiatomeo).

***

### [gittogit](https://github.com/dariodip/gittogit)
#### Dec 2017 - Mar 2018

gittogit is a simple implementation of the git protocol using a peer-to-peer network as a storage. The storage is, indeed, a Distributed Hash Table (DHT). We used Tomp2p as DHT library.
Each client can:
1. create a repository in a directory;
2. commit the repository (if there were changes);
3. add new files not yet tracked;
4. pull and push its repository on the DHT. The system will notify the user in case of conflicts (e.g. pulling a modified repository, and so on).
Along with Tomp2p we used Travis CI for Continuous Integration, jUnit for Unit Tests, TextIO for reading and writing text and for the CLI.

The project was developed together with [Dario Castellano](https://github.com/dariocast).

***

### [WSIL](https://github.com/criticalerrors/WSIL) [(Online on Heroku)](http://wsilang.herokuapp.com/)
#### Mar 2017 - Jun 2017

 WSIL is a web app giving the opportunity to check out trending of programming languages and frameworks. Using WSIL you can both see jobs for a given programming language or framework, with courses concern it.
On WSIL you can find statistics to closely analyze up to 200 programming languages and up to 100 frameworks.
For each programming language and framework, you can find:
- count of StackOverflow answers;
- jobs for it, obtained from AuthenticJobs and Indeed;
- course for it, obtained from Coursera and Udacity;
- trend for it in each region and time interval, based on GitHub repositories activity and Google Trends.

Data are obtained from the following sources:
- Wikipedia;
- StackOverflow;
- GitHub;
- AuthenticJobs;
- Indeed;
- Coursera;
- Google Trends;
- Udacity.

The technology stack is the following:
- Django as back-end, using Django Rest Framework for REST APIs;
- Plotly for showing graphs;
- Jinja + React + Bootstrap for front-end and UI;
- SQLite as a database;
- Scrapy for scraping.

The project was developed together with [Mattia Tomeo](https://github.com/mattiatomeo) and Fabio Napoli.

***

### [rfd-discovery ](http://github.com/dariodip/rfd-discovery)
#### Oct 2016 – Feb 2017

  rfd-discovery is a tool written in Python and Cython using the Scipy stack.
This project deals with the discovery of Relaxed Functional Dependencies(RFDs) using a bottom-up approach: instead of taking a fixed threshold on input and finding all the RFDs, this method infers distances from different RHS attributes by itself and then discovers the RFDs for these ones.
rfd-discovery takes a dataset, representing a relational table, in CSV format as input and prints the set of the discovered RFDs.
We also built a simple page, using AngularJS as frontend and Flask as backend, in order to easily upload CSV files and interactively select right-hand-side and left-hand-side.

The project was developed together with [Mattia Tomeo](https://github.com/mattiatomeo) and [Antonio Altamura](https://github.com/antonioaltamura).

***

### Healthy Weight
#### Apr 2015 – Jul 2015

  This project was developed for the course in Human Computer Interaction at the University of Salerno. It consists of a small app, developed with C#, for tracking exercise and physical health, aimed at countering obesity. The application, related materials and prototyping activities, are mainly focused on keeping up the principle of usability, based on the main guidelines and heuristics.

The project was developed together with Christian De Blasio, Domenico Iannone and Marco Picariello.

## Contact me

[darionovantadue@gmail.com](mailto:darionovantadue@gmail.com)
