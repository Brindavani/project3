## 	Network Visualization of Flora(Plants) and Fauna(animals):

Please click to watch the overview video.

[![video](https://github.com/aravindkattamuri/Project-2/blob/master/4.png)](https://youtu.be/OU7WBCknZqQ)

This project is created by students: Aravind Kattamuri, Bharath Kumar Kande, Brindavani Sunkari, Praneeth Yerramothu of Texas Tech University - Department of Computer Science on 12/11/2016 with reference to the course Project 3 of CS5331-004: Visualization and Visual Analytics course. This project is a novel web application and *visualization* that we have created using javascript, html, and D3.js for *Network Visualization of Flora(Plants) and Fauna(animals)*.  

### Highlights of features implemented in this project:

**First:** We have used the 2 data sources : 

1. The JSON file data (roughly 3.3M) contains the information about Flora(Plants) and Fauna(animals) classification, their description, Locations mostly found and  their food information. The information to create this file has been collected from different Web Sites/sources.

2. The data to show various species distribution on earth visualization has been obtained from the *onezoom* website that is available [here](http://www.onezoom.org/).  
 
We preprocessed the data to get the required visualization for this project3. Coming to the data description, we worked on the the data sources mentioned earlier. Below is the screen-shot of the data from the data files. The main focus of our project is on showing the Animal & plant classification and their food-chain relationship using D3.js for data visualization. 


![ScreenShot](https://github.com/aravindkattamuri/Project-2/blob/master/1.png)


![ScreenShot](https://github.com/aravindkattamuri/Project-2/blob/master/2.png)


**Second:**  We have visualized the classification of Flora(Plants) and Fauna(animals) along with their food-chain relationship. Created a Stacking/Touching visualization using D3.js to represent this data. 
When a user selects a particular node on the Touching visualization, it highlights their food-chain relationship in that visualization. We also allow users to mouse-over these nodes to see the corresponding category/name.  Mouse-over on the leaf nodes also displays the image of that plant/animal.

![ScreenShot](https://github.com/aravindkattamuri/Project-2/blob/master/3.png)


![ScreenShot](https://github.com/aravindkattamuri/Project-2/blob/master/4.png)


**Third:** We have also visualized the locations/counties in which the animal habitat is mostly found on the world map. This also shows the migration information of some animals using 3D axial lines on the map. This allows the user of our web application to visualize the locations and migration information very easily. 


![ScreenShot](https://github.com/aravindkattamuri/Project-2/blob/master/5.png)


**Finally:** To give the user an overview of the habitat with their species distribution along with their conservation status on the earth, a dashboard with pie-chart and bar-chart has been designed. Each of the categories is represented using different colours. When a user mouse-overs on a particular pie, it shows the percentage of the distribution of it's species on the earth.
When a user clicks on some category in the pie-chart, the bar-chart shows the corresponding 'Conservation Status Breakdown' in the same colour as in the pie-chart for that category.    

![ScreenShot](https://github.com/aravindkattamuri/Project-2/blob/master/7.png)


### Interesting findings:

From the visualization of this data , we can find some interesting events in the data like:

**1.** 

![ScreenShot](https://github.com/aravindkattamuri/Project-2/blob/master/10.png)



**2.** 

![ScreenShot](https://github.com/aravindkattamuri/Project-2/blob/master/11.png)


**3.** 

![ScreenShot](https://github.com/aravindkattamuri/Project-2/blob/master/12.png)


**4.** 

![ScreenShot](https://github.com/aravindkattamuri/Project-2/blob/master/13.png)


**5.** 

![ScreenShot](https://github.com/aravindkattamuri/Project-2/blob/master/8.png)


### Duties of each student in our group:


Our Project 3 is a group of 4 students: Aravind Kattamuri, Bharath Kumar Kande, Brindavani Sunkari, Praneeth Yerramothu. 
Bharath Kumar Kande is the leader of this group. Below are the duties of each student in our group: 

**Aravind Kattamuri:**  Aravind Kattamuri mainly worked on
1.Creating the dataset for this project by working with Brindavani Sunkari and Praneeth Yerramothu.
2.Creating and integrating the dashboard that has Bar-chart and Pie-chart that represents the Species Distribution & their Conservation Status respectively using D3.js. 
3.Creating report for this project by working with Praneeth Yerramothu and Brindavani Sunkari.

**Bharath Kumar Kande:** Bharath Kumar Kande worked on 
1. Creating a good front-end design for this project.
2. He is the lead in designing/creating a Touching visualization for representing Tree structure that shows both Hierachial data for classification and Network for Non-Hierachial data to show food-chain relationship with animation.
3. Integration of other modules of project that each team member have worked on: the world-map and dashboard Visualizations.
4. Showing the images on the Touching visualization on mouse-over.

**Brindavani Sunkari:** Brindavani Sunkari worked on 
1. Creating the dataset for this project. 
2. Identifying interesting events in the data with Praneeth Yerramothu.
3. Creating the report with Aravind Kattamuri and Praneeth Yerramothu.
 
**Praneeth Yerramothu:** Praneeth Yerramothu worked on 
1. Creating the dataset for this project.
2. He is the lead in visualizing network on world map based on the data retrieved and on the information on Migration of Animals. 
3. He also worked on data research. 
4. Creating the report with Brindavani Sunkari and Aravind Kattamuri.


### Software required for the implementation this Project

The following are the Software that we have used to create this visualization:

1. *Sublime Text editor*. It can be downloaded from [here](https://www.sublimetext.com/download).

2. *D3.js*. It can be downloaded from [here](https://d3js.org/).

3. *live-server*. Instructions to setup are available [here](https://github.com/tapio/live-server). 

4. *Node.js*. It is required for set up of live-server. It can be downloaded from [here](https://nodejs.org/en/download/).

### Steps to run

1. Place all the relevant files in the same folder. 

2. Start the live-server using live-server command.

3. Select the project html file (index.html file in this case).
 
### Our web application link

To view our web application of *Network Visualization of Flora(Plants) and Fauna(animals)*, please click [here](https://bharathkande.github.io/project3/index.html).

### Acknowledgments
This is project has been implemented by Aravind Kattamuri, Bharath Kumar Kande, Brindavani Sunkari, Praneeth Yerramothu under the esteemed guidance of professor [Tommy Dang](http://www.myweb.ttu.edu/tnhondan/) at Texas Tech University.
