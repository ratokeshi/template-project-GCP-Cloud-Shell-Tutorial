# template-project-GCP-Cloud-Shell-Tutorial
Template project for a cloud shell tutorial  
DeleteMe- Find all sections that say DeleteMe, these should be deleted.  
ReplaceMe- Sections, keywords, id numbers that need to be replaced or personalized.  
VerifyMe/- Text thatmight apply for all instances but you might want to look to see if there is new information.  

ToDo List before going to production:
- [ ] Check for and note locations of VerifyMe 
- [ ] Check for and note locations of ReplaceMe 
- [ ] Check for and note locations of DeleteMe 
- [ ] Change GCP Lab number references
- [ ] Change Lab Title references
- [ ] Change Lab Quests references
- [ ] Change Overview references
- [ ] Change Objective references
- [ ] Change video references
- [ ] Change Get started references if there are specific details associated with this lab.
- [ ] First Run through
- [ ] Second Runthrough for ease of use
- [ ] Third Runthrough for special details and learn more references.
- [ ] Change or add lab verification links in Qwiklab documentation 
- [ ] Check for and delete VerifyMe 
- [ ] Check for ReplaceMe 
- [ ] Check for DeleteMe 
- [ ] Check for The Markup references at the end of the template and delete them.


Lab ID: [ReplaceMe get from Qwiklab]

# Cloud-Shell-GSP###ReplaceMe-ReplaceMeNameOfLab
[Overview from Lab Guide]

[https://google.qwiklabs.com/focuses/ReplaceMe?parent=catalog](https://google.qwiklabs.com/focuses/ReplaceMe?parent=catalog)

This lab is also part of the [ReplaceMe](https://google.qwiklabs.com/quests/ReplaceMexxxx) Quest


## Overview
ReplaceMeTextFromOverview


### Objectives
In this lab, you learn how to perform these tasks:

ReplaceMeOjectives

### What you'll need
The Google Chrome browser. Other browsers are currently not supported by some parts of GCP suckh as Cloud Dataprep.

### What you'll learn
ReplaceMeWhatYouWillLearn

### Here are some links: 
[ReplaceMeLinkName](ReplaceMeLink) ReplaceMeDescription


### Here are videos for your use:  
[ReplaceMeLinkName](ReplaceMeLink) ReplaceMeDescription
Examples:
[Cloud Dataprep on GCP](https://www.youtube.com/results?search_query=%22Google+Cloud+Platform%22+%22cloud+dataprep%22)  
[Advanced Data Cleanup Techniques using Cloud Dataprep (Cloud Next '19)](https://www.youtube.com/watch?v=etgirLS6s_A)  
[Data and Insight course with Google Cloud Platform | BigQuery | Big Data](https://www.youtube.com/watch?v=kNrnz5PWBuU)  
[Creating ETL Jobs with DataPrep - Take5](https://www.youtube.com/watch?v=DEh3pZIgJ9k)  
[Cloud OnAir: CE Chat: Wrangling Your Data with Cloud Dataprep](https://www.youtube.com/watch?v=GszTc7H5uHw)  


### Get Started:
To begin the tutorial in a Qwiklab open your Google Cloud Consoles as you normally would.
1.  If you have issues with the console try using incognito mode and go to https://console.cloud.google.com/
2.  If you are in the student session of the GCP Console, click the Cloud Shell icn on the top right that looks like this: ![alt text](https://walkthroughs.googleusercontent.com/tutorial/resources/cloud-shell-icon-v1.svg "Cloud Shell Icon on the top right of the GCP Console")
3.  Enter the following commands to clone this repository and launch the turotial.
```bash
git clone https://github.com/ratokeshi/Cloud-Shell-GSPReplaceMeNumber-ReplaceMeName.git
&& cd template-project-GCP-Cloud-Shell-Tutorial && cloudshell launch-tutorial tutorial.md
```

```bash
gcloud config configurations create qwiklab-$(date +%s)
gcloud config unset project
gcloud auth login <google5150507_student@qwiklabs.net>
gcloud config set project <from Lab>
cloudshell launch-tutorial tutorial.md
```


To begin the tutorial in your currently authenticated Google account, click on the button given below:
[![Open in Cloud Shell](http://gstatic.com/cloudssh/images/open-btn.png)](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/ratokeshi/Cloud-Shell-GSPReplaceMeNumber-ReplaceMeFolder.md)
