# [Network Visualization on Circle of Life] (https://bharathkande.github.io/project3/)

This project is a web based application that facilitates hierarchical and geographical network view of the living things that are co-dependent on each other. The Project Team members are [Bharath Kumar Kande](https://github.com/bharathkande), [Brindavani Sunkari](https://github.com/Brindavani), [Praneeth Yerramothu](https://github.com/praneethyerramothu), [Aravind Kattamuri](https://github.com/aravindkattamuri).

## Video presentation
Click on the thumbnail to play the video.

**Presents the video**


To visualize the network that we have created, click [here](https://bharathkande.github.io/project3/)

## Table of contents

-	[Overview of the Project](#Overview-of-the-project)
-	[Network on a Stack diagram](#Network-on-a-stack)
-	[Network on a Geographical Map](#Network-on-a-Geographical-Map)
-	[Interesting Findings](#Interesting-Findings)
-	[Duties of each Student](#Duties-of-each-Student)
-	[Software used for developing application](#Software-used-for-developing-application)
-	[Steps to run the application](#Steps-to-run-the-application)
-	[Acknowledgement](#Acknowledgement)



## Overview of the project

**screenshot of the entire project**

We have created this very informative tool to depict how the balance in prey-predator relationship is maintained and to show the natural behavior of all the living things in the network. On the left side of the screen, we visualize the relationship(Predator-Prey) between the living things by using links to connect the related living things. On the right side of the screen, we primarily intend to visualize the migration paths of the migratory animals (Mammals, Birds, Insects and Fishes etc.). The application also displays the top frequent places where a particular animal is found the most.

## Data sources

http://www.arkive.org
https://www.worldwildlife.org
http://www.onezoom.org/

## Network on a stack Diagram

The living Organisms are broadly categorized into two categories i.e. Flora (Plant Life) and Fauna (Animal Life). These are further divided into several categories and these are clearly visualized using the linearly aligned Stack diagram. The complete hierarchy of living organisms along with the examples is displayed in the stack diagram. The examples are displayed as leaf nodes. The Stack diagram has several features that makes the visualization better.
The features that are included in the Stack diagram are listed below:
1. When hovered over a node, the information about that node is displayed. 
2. When hovered over the leaf nodes, the images are displayed.
3. Predator-Prey relationship is also visualized in the network.
   When the leaf node is clicked, the prey of that node is shown.
4. When the leaf node is clicked, along with the prey it also shows the brief   information about that organism. The User can be redirected to the Wikipedia page about that node If “More Info” is needed.
5. If more than one predator-prey relationship is displayed, the user can click one leaf node to see the prey of that node.
In the above case the relationship is shown using Animation.
6. Instead of selecting each leaf node separately to see the predator-prey relationship, the user can click on above node/hierarchy.
7. The Map is integrated with the stack diagram to show the below features.
a. The migrating birds are shown in the map using animation.
b. When a leaf node is selected, the top 10 locations in which that animal’s population is dense are displayed.

** Brindavani’s data**

## Network on a Geographical Map

The Geographical map is integrated with the linearly aligned Stacked diagram to optimize the use of inline functionality of the code. The elements and the attributes that are used to visualize network on the map, however, are almost independent of the stacked diagram. 
The map is used to display the migration paths of various living things. Every migratory animal or a living thing has to travel considerable amount of distance for the sake of breading, feeding and for, more importantly, survival. In this Visualization, we have considered those living migratory things that travel a lot of distance just for food or for breeding. These animals travel 10000s miles every year to a place where they have to migrate to survive.

**screenshot-bird migrating**

In the above picture, we have visualized a bird migrating from one place to another place. For the unique representation of migrating animals, we have used Animations. These animations help us to visually keep track of the migrating animals and its current position in its migrating path.


**screenshot- points plotting **

We made it possible to integrate the elements in the Stacking/Touching diagram and the geographical map itself. When an animal in the Stacking diagram is clicked, the top locations where it is frequently found or the locations where it is more in number are appended to the map. The points that are plotted on the map are in respect to the locations they are frequently found in.


## Interesting Findings	

**Write and take screen shots of interesting findings**


## Duties of each Student

**Bharath Kumar Kande** :

**Aravind Kattamuri**:

**Brindavani Sunkari**:

**Praneeth Yerramothu**:


## Software used for developing application:

We have used the following software for implementing ,

1.	[Brackets](http://brackets.io/) for MAC / [Sublime Text Editor](https://www.sublimetext.com/) for Windows.
2.	The library, [D3.js](https://d3js.org/) .
3.	A live server(optional).
4.	Node.js (required when a live server is used).


## Steps to run the application

There are two methods to run this application,

1.	Open any web browser and type in the url – “https://bharathkande.github.io/project3/“ and hit send for direct access with no modifying rights.
2.	Find the repository called “project3” on github by typing the name on in the repository search bar. Download the repository and run the main html file called, “index.html”.


## Acknowledgement

This is project has been implemented by Aravind Kattamuri, Bharath Kumar Kande, Brindavani Sunkari, Praneeth Yerramothu under the esteemed guidance of professor [Tommy Dang](https://github.com/Tommy-Dang) at Texas Tech University.
