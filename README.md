![ulupong](ulupong.png?raw=true "ulupong")

<h1><center>Inbuilding Detection: Proof of Concept</center></h1>


### Project: Detection of In-Building use of Network Equipment

### Table of Contents
1. [Project Motivation](#pm)
2. [Project Goal](#goal)
3. [Notes](#notes)
4. [Data](#data)
5. [Install](#install)
6. [Contents](#contents)
7. [Related Blogs](#blog)

#### Project Motivation<a name="pm"></a>
 As an engineer for a data company, providing that extra mile for better customer service, is always a great motivation. Appropriate service can be provided once this is known, thus better overall experience for the paying customer.

#### What is this project trying to achieve?<a name="goal"></a>
This project is a proof of concept to provide an answer on determining in-building use **without** the use of sensors.<br>
However, before I even get there, I also wanted to know if these readily available data have potential for ML.<br>
Data used for this proof-of-concept is sourced out entirely from usage metrics and kpis.<br>
Last but not least, though beyond my current skill set, I need to know if there is a way for these data to find home on Unsupervised Learning.

#### Notes<a name="notes"></a>
I have anonymized the measures so that values are arbitrary to all people outside my line of work.

#### Data <a name="data"></a>
The CSV that holds the data are raw export of network metrics. The file is pre-processed for anonymity to make values  arbitrary to all people outside my line of work. However it is worth noting that no other manipulations outside the project code were done. More information on the data is embedded in the Jupyter Notebook file.

#### Install<a name="install"></a>
This project requires Python and the following Python libraries installed:

- NumPy
- Pandas
- matplotlib
- seaborn
- scikit-learn
- imbalance-learn

You will also need to have software installed to run and execute a Jupyter Notebook.<br>
If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more include.

#### Content<a name="contents"></a>
The archive submission includes the following files:<br>
1. An Jupyter Notebook file that runs the Project Code (inbuilding_detector_01.ipynb)<br>
2. A 3MB CSV file that contains the project data (equipment_data_parsed.csv)<br>
4. Icon image file (u1up0ng.png)
3. This README.md file


#### Related Blog<a name="blog"></a>
Please find link to the blog related to this project: [UnSensored Device Detection](https://medium.com/@u1upong/inside-outside-without-sensors-ad3060d9f4dd)

> This is my first take on a full blown ML Project. I Appreciate your consideration

**u1up0ng 2020/06/26**