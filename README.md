
<!--
author:  Thanu

email:    thanu.nakshathra@gmail.com

version:  0.0.1

language: en

narrator: US English Female
script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js
          https://felixhao28.github.io/JSCPP/dist/JSCPP.es5.min.js

import: https://raw.githubusercontent.com/LiaTemplates/algebrite/0.2.1/README.md 
        https://raw.githubusercontent.com/liaTemplates/TextAnalysis/main/README.md

-->

# DevOps
DevOps is a set of practices that combines software development (Dev) and IT operations (Ops) to shorten the systems development life cycle and provide continuous delivery with high software quality. 

Jenkins is a popular DevOps tool that helps teams automate their software development process and achieve continuous integration, continuous delivery, and continuous deployment. 

By using Jenkins, teams can streamline their DevOps pipeline and optimize their software delivery process, resulting in faster time-to-market and higher-quality software.

## Steps in DevOps

* Version control: Source code management
* Continuous Integration (CI): Build ,compile, validate, review, testing
* Continuous Delivery: Deploy in test server
* Continuous Deployment (CD): Deploy in production server


# Jenkins

## Introduction

Jenkins is an open-source automation server used for building, testing, and deploying software applications. It automates the non-human part of the software development process, thereby freeing up developers' time to focus on more critical tasks.

Some of the key features of Jenkins include continuous integration, continuous delivery, and continuous deployment. 

By automating the build, test, and deployment processes, Jenkins enables teams to detect and fix issues early in the development cycle, resulting in faster time-to-market and higher-quality software.

Jenkins is highly customizable and has over 1,500 plugins available to extend its functionality. It supports a wide range of programming languages and integrates with many popular tools and services such as GitHub, Docker, and AWS.

Overall, Jenkins is a powerful automation server that can help teams of all sizes streamline their software development process and deliver better software faster.


![Jenkins Pipeline](/img/JenkinsPipeline.png)



## Install Jenkins on windows

Download Jenkins for windows (LTS Version) [Download here](https://www.jenkins.io/download/thank-you-downloading-windows-installer-stable/)

Install Jenkins  [Follow these steps](
https://www.jenkins.io/doc/book/installing/windows/ )

On successful installation, you should be able to access Jenkins in localhost:8080 

## Getting Started with Jenkins 

* Open your browser at localhost 8080
    ![Unlock Jenkins](/img/JenkinStart.png)
* Get the password from the path given above and paste it and click continue
    ![Install Plugins](/img/InstallPlugins.png)
* Select **Install suggested plugins** & wait till the process completes
* Once process completes, it redirects to,
    ![Create Jenkin User](/img/CreateJenkinUser.png)
* Create user & fill up the details , save & continue
* Click save and finish 
* Now you can access jenkins in localhost:8080 with your created user & password
    ![Jenkins Home](/img/JenkinsHome.png)

