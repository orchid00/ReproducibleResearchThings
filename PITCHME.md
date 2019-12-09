---
type: slide
slideOptions:
  transition: slide
---

# Reproducible Research

**Paula Andrea Martinez | National Imaging Facility**
2019-12-10

---

### Acknowledgement 

> @AmandaMiottoGU and 
> @JulieToohey from Griffith University, 
> authors of the original materials, last updated on 2019-07-08, CC BY-NC 4.0
> https://github.com/guereslib/Reproducible-Research-Things

---

## What is Reproducible Research?

---

![image](https://github.com/guereslib/Reproducible-Research-Things/raw/master/images/repeat-after-me-004-c4c849.jpeg =100x20)

Source: https://thenib.com

---

## Why is it Important?

---

![image](https://github.com/guereslib/Reproducible-Research-Things/raw/master/images/reproducibility-graphic-online3.jpg&size=auto 70%)

Source: [Nature doi:10.1038/533452a](https://www.nature.com/news/polopoly_fs/7.36718.1464174471!/image/reproducibility-graphic-online3.jpg_gen/derivatives/landscape_630/reproducibility-graphic-online3.jpg)

---

No one wants their research to be `retracted`

* some data were missing
* untracked version of changes
* mistakes were made
  * true error
  * fraud
  
---

### Today we are going to learn 9 lessons to safeguard us against these situations

---

### Let's look at some scenarios....

---

### What if a key person from your lab disappeared one day? 
(family or personal emergency, no longer contactable)

---

* Could you all continue your work?
* Would you know where all `the data` is stored?
* Could you keep running effectively for 1 month?

`1 year?`

---

![image](https://github.com/guereslib/Reproducible-Research-Things/raw/master/images/376c2ff9d8260fa7c1ae4a3468e1bce9.jpg)
Source: [Upturned Microscope](https://theupturnedmicroscope.com/comic/real-vs-movie-scientist-3/)

---

### Let's look at a few tools we can use to protect our research

---

## Documentation
### Naming Conventions
### Folder Structures
### Automation
### Version Control

---

## Step1 
## Documentation

---

Documentation is all the material that provides official information or evidence of procedures,

so that an outsider could understand the workings of your lab/experiment. 

---

This can include where your results and working data are saved. 
Lab notebooks and digital copies are saved in a safe place (such as research storage).
* Make sure these are saved somewhere that's accessible to your supervisor/team. 

---

Have you got a new staff member coming onboard to your team? 

Do they have access to `documentation`?

---

Documentation will also be important for any audits in your lab or if someone would like to reproduce your research.

---

`Documentation is a love letter to your future self - 
Damian Conway`

---

### Exercises!

---

#### Beginner

Read this first: [How to start documenting](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/2.-Organise-Document/Documentation-and-metadata) by CESSDA

* Any start is a good start
* Start with documenting in a text file or document 
* Automatically sync to the cloud (in a shared place*) such as:
  - OneDrive, Microsoft teams, AWS

---

#### Intermediate

Once you have the basics in place, go into detail on how your workflow goes from raw data to the finished results. 

This can be anything from the location of the data to the code you use to create results.

---

#### For all

Now that you've got a good head start, time to learn about [Git Repositories](https://rogerdudler.github.io/git-guide/) and [wikis](https://help.github.com/en/github/building-a-strong-community/about-wikis).

- A wiki is a collection of collaboratively authored web documents that help solve a problem.
- Talk to eResearch support or the Library

---

### External Resources

* [British Ecology Reproducibility Book](https://www.britishecologicalsociety.org/wp-content/uploads/2017/12/guide-to-reproducible-code.pdf)
* [How to start documenting](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/2.-Organise-Document/Documentation-and-metadata) by CESSDA
* [Software Carpentry Git Workshop](https://swcarpentry.github.io/git-novice/)

---


### Documentation
## Naming Conventions
### Folder Structures
### Automation
### Version Control

---

## Step2
## Naming Conventions

--- 

### What is a File Naming Convention?

A File Naming Convention (FNC) is a framework or protocol if you like for naming your files in a way that describes what files contain and importantly, how they relate to other files. It is essential before collecting data to establish an agreed FNC.  

---

### What are the benefits of using a file naming convention? 

Naming files consistently, logically and in a predictably will prevent against unorganised files, misplaced or lost data.  It could also prevent possible backlogs or project delays. A file naming convention will ensure files are:

---

* Easier to process - All team members won't have to `overthink` the file naming process 
* Easier to facilitate `access`, `retrieval` and storage of files
* Easier to browse through files `saving time and effort` 
* `Harder to lose!`

---

* Having logical and known naming conventions in place can also help you with version control
* Check for obsolete or duplicate records

---

Former PhD student and subsequent founder of the Figshare platform, Mark Hahnel, typified a common challenge: 

---

>*‘During my PhD I was never good at managing my research data. I had so many different file names for my data that I always 
> struggled to find the correct file quickly and easily when it was requested. My former PI was so horrified upon seeing
> the state of my data organisation that she held an emergency lab book meeting with the rest of my group when I was leaving’. 
> - Research Information, April/May 2014  

---

### Coming up with a plan for your team on how to name files.

It will be best if you start this early.

---

Your research team should agree on the following elements of a file name prior to data collection:

* Vocabulary - choose a standard vocabulary for file names, so that everyone uses a common language
* Punctuation - decide when to use punctuation symbols, capitals and hyphens
* Dates - agree on a logical use of dates so that they display chronologically i.e. YYYY-MM-DD `ISO 8601`

---

* Order - confirm which element should go first, so that files on the same theme are listed together and can therefore be found easily
* Numbers - specify the amount of digits that will be used in numbering so that files are listed numerically e.g. 01, 002, etc.

---

As suggested, consistent and meaningful naming of files and folders can make everyone’s life easier. See this example below:

* YYYYMMDD__SiteA_SensorB.csv
* Date__Location_Sensor.extension

Which when applied, would look like this below

20150621__Yaouk_Humidity.csv

---

Some characters may have special meaning to the operating system so avoid using these characters when you are naming files. These characters include the following: 

> / \ " ' * ; - ? [ ] ( ) ~ ! $ { } &lt > # @ & | space tab newline 

Source : [IMB file name support](https://www.ibm.com/support/knowledgecenter/en/ssw_aix_71/com.ibm.aix.osdevice/filename_conv.htm).

--- 

### Exercises!

---

#### Beginner

Let's look at some naming convention for your data files and documents. 
* Any dates are best stored with YYYYMMDD.
* Try to avoid spaces in your file names.

Which files can you already rename to follow this new convention?

---

#### Intermediate

The University of Edinburgh has a comprehensive and easy to follow list (with examples and explanations) the [13 Rules for file naming conventions](https://www.ed.ac.uk/records-management/guidance/records/practical-guidance/naming-conventions).

Make sure you follow 13 Rules for file naming conventions within your project files.

---

#### Advanced

Do you have a policy in your team around naming conventions? If not, this is a great way of getting everyone on the same page. 
This will go on Documentation. - Remember that wiki we were talking about?

---

### Internal Resources

* Talk to your eResearch Support or the Library services

---

### External Resources
* [Naming things by Jenny Bryan](https://speakerdeck.com/jennybc/how-to-name-files)
* [File naming and folder conventions by CESSDA](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/2.-Organise-Document/File-naming-and-folder-structure) 
* [The University of Edinburgh, the 13 Rules for file naming conventions](https://www.ed.ac.uk/records-management/guidance/records/practical-guidance/naming-conventions)

---

### Documentation
### Naming Conventions
## Folder Structures
### Automation
### Version Control

---

## Step 3 
## Folder Structures

---


### Documentation
### Naming Conventions
### Folder Structures
## Automation
### Version Control

---

## Step 4
## Automation

---


### Documentation
### Naming Conventions
### Folder Structures
### Automation
## Version Control

---
## Step 5
## Version Control

---

### Great! 
By implementing these steps, we've already improved our processes!

`Now if someone leaves our lab, we're covered!`

---

### Next Scenario....

---

### Imagine your laptop and hard drives are lost or damaged? 

---

* Could you continue your work?
* Is your data backed up?
* Encrypted?

---

### Let's look at a few tools we can use to protect our research

---

### Backing up to the cloud
### Computer Security
### Deidentifying your data

---

![image](https://github.com/guereslib/Reproducible-Research-Things/raw/master/images/phd103003s.gif)

Source: PHDcomics

---

## Step6
## Cloud Backup

--- 

Note:
While Computer security isn't really about reproducibility, it is important. Plus I wanted to highlight encrypting hard drives

---

## Step 7
## Computer Security

--- 

## Step 8
## Deidentifying your data

--- 

### So now we have some new skills up our sleeve
### If our laptop goes missing, we are better prepared

---
Now let's look at after a project has finished

---

### Next Scenario....

---

Someone has published contradicting results to your published paper, and you've been asked to provide your data and methods. 

`Could you?`

---

![image](https://github.com/guereslib/Reproducible-Research-Things/raw/master/images/phd031214s.png =450x400)

Source: PHDcomics

---

We're already covered some things that can help us

---

* Storing our data in the cloud
* Documentation
* Versions of software

---

## Step 9
## Digital Object Identifier (DOI) and Persistent identifier (PiD)

---

Wow, that's 9 Reproducible Research things! 

---

What if we look at another scenario?

---

if a research partner organization believes your "sensitive" data has been made available to others (ie a data breach). Could you show that steps were taken to avoid this or show that it couldn't happen?

---

Turns out, we can!

---

* Owncloud or Research Space – tracing who you have shared a file (Step 6 Cloud Backups)
* Computer encryption (Step 7 Good Computer Safety)
* General good computer safety – unique passwords and use Multi factor Auth when possible (Step 7 Good Computer Safety)
* Separating identified variables (Step 8- Deidentifying your data)

---

Amazing! We have so many new skills!

---

What changes are you going to make?

---

![image](https://github.com/guereslib/Reproducible-Research-Things/raw/master/images/repeat-after-me-50-3a3504.jpeg)

Note:the nib.com Repeat after me comic

---

Thank you for coming!

