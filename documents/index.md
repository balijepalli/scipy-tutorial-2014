# Agenda

[TOC]


## 8:00 am First Session

### Getting Started

* Get acquainted and verify preparations (5 min) - Matt
    * Say *Hi!* to the instructors
    * Introduce yourself to the person sitting next to you, they will be your
  partner
    * Recall successfully completing the [preparation](Preparation.md) tasks
    * Interact with other participants throughout the tutorial on [the
      MoPad](https://scipy2014.etherpad.mozilla.org/13)

### Introduction

[History and Motivation for Reproducible Research](http://reproducible-research.github.io/Reproducible-Research-Part-I/) (10 min) <a class="youtube-video-link" href="https://www.youtube.com/watch?v=EzX7MN_bzqg#t=147">History and Motivation for Reproducible Research video</a> - Luis

* History of scientific societies and publications
    * [Leeuwenhoek](http://en.wikipedia.org/wiki/Antonie_van_Leeuwenhoek) was The Man!
    * [The Invisible College](http://en.wikipedia.org/wiki/Invisible_College)
    * [Nullius in Verba](https://royalsociety.org/about-us/history/)

### Data Acquisition

[Image Acquisition](DataAcquisition.md) (25 min) - Matt

* Replication of the early microscope experiments by Antonie Leeuwenhoek
    * Cell camera phone microscope
    * With drop of interesting water
    * *Hands on:* each pair acquires images

### Data Sharing

[Data Sharing](DataSharing.md) - (20 min) <a class="youtube-video-link" href="https://www.youtube.com/watch?feature=player_detailpage&v=EzX7MN_bzqg#t=2321">History and Motivation for Reproducible Research video</a> - Luis

* Image gathering, storage, and sharing (10 min)
    * Figshare (www.figshare.com)
    * *Hands on:* Upload the images
* Download data via RESTful API (10 min)
    * REST download via Python standard library
    * Checksum verification
    * *Hands on:* Download the data via HTTP


## 9:00 am Second Session

### Reproducible Computational Environment

[Computational Environment](ComputationalEnvironment.md) (20 min) <a class="youtube-video-link" href="https://www.youtube.com/watch?feature=player_detailpage&v=EzX7MN_bzqg#t=3920">History and Motivation for Reproducible Research video</a> - Aashish

* Reproducible computational environment
    * Docker
    * Package versioning
    * Virtual Machines
    * Cloud services
* *Hands on:*
    * Create a Docker image and container
    * Run our tutorial package verification script
    * Upload your Docker image to DockerHub

### Developing Reproducible Scripts and Modules

[IPython Notebook, Scripts, and SimpleITK](DataProcessing.md) (20 min) <a class="youtube-video-link" href="https://www.youtube.com/watch?feature=player_detailpage&v=EzX7MN_bzqg#t=5288">History and Motivation for Reproducible Research video</a> - Matt

* Reproducible code development
    * IPython Notebook to combine notes, code, and results
    * Avoid duplication with re-usable modules
* *Hands on:*
    * Run analysis on new data
    * Generate histogram for the data

### Revision Control

[Revision Control with Git and GitHub](VersionControl.md) (20 min) <a class="youtube-video-link" href="https://www.youtube.com/watch?feature=player_detailpage&v=EzX7MN_bzqg#t=6445">History and Motivation for Reproducible Research video</a> - Steve

* Software versioning, collaboration, and citation
    * Keeping track of changes
    * Unique hashes
    * DOI
* *Hands on:*
    * Create a branch
    * Make a commit
    * Push the branch
    * [Create a citable version](https://guides.github.com/activities/citable-code/)


## 10:00 am Break (15 min)


## 10:15 am Third Session

### Regression Testing

[Regression Testing](RegressionTesting.md) (30 min) <a class="youtube-video-link" href="https://www.youtube.com/watch?feature=player_detailpage&v=HCyHn_by3N0#t=56">History and Motivation for Reproducible Research video</a> - Jc

* Quality code development with regression tests
    * Testing code hypothesis: the scientific method applied to development
    * Unit testing
    * Integration testing
    * Continuous integration dashboards
* *Hands on:*
    * Run the test suite
    * Add coverage for another method to the unit tests

### Literate Programming

Literate Programming with Dexy (30 min) <a class="youtube-video-link" href="https://www.youtube.com/watch?feature=player_detailpage&v=HCyHn_by3N0#t=1634">History and Motivation for Reproducible Research video</a> - Ana

* Article generation
* RST to HTML, etc
* GitHub replication and sharing
* *Hands on:* run dexy to generate a PDF document


## 11:15 am Fourth Session

### Open Science Publication

Submitting an article to a Reproducible Journal (20 min) <a class="youtube-video-link" href="https://www.youtube.com/watch?feature=player_detailpage&v=HCyHn_by3N0#t=5322">History and Motivation for Reproducible Research video</a> - Luis

* Open Science Publication
    * Open Access
    * Publishes article, data, and code
* *Hands on:*
    * Submit Article to the [Insight Journal](http://insight-journal.org/browse/journal/74)
    * Point to GitHub fork for source code

### Replicate or Perish !

Attempt to replicate your peers' articles (40 min)

* Replicate the publications of groups next to you
* Share your observations
