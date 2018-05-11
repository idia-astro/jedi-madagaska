# jedi-madagaska
Resources for the JEDI Workshop organised in conjunction with the May 2018 MadagaSKA Conference

## Projects
### Astronomy : Radio Source Detection and Classification. - Russ Taylor & Imogen Whittam.

Automated detection and classification of radio astronomy signals is becoming increasingly important with the dramatic growth of image data sets from next generation radio interferometer telescopes.  In this project we will depoy and analyse algorithms to automatically detect and measure astronomical radio emission in images from data taken by SKA pathfinder radio telescopes.  We will also develop analytical tools and statistical, intelligent approaches to identifying complex, multiple and component signals in the image data.

### Health : Image-based data mining to improve radiotherapy for cancer treatment - Andrew Green. 

Radiotherapy is a treatment for cancer in which radiation is directed into the patient to kill cancerous cells. Unfortunately sometimes the treatment does not work. In this project we will use data from several radiotherapy treatments to try and correlate the radiation dose with, for example, survival/recurrence aiming to improve radiotherapy for future patients. The project will follow the whole process of image-based data mining, including the use of tools to perform image registration and analysis techniques to interrogate the data.

### Astronomy : Machine Learning for extracting Stellar Rotation Periods from Kepler data - Anna Scaife
Stars spin – and the rate at which they spin has a profound effect on their health.  So measuring the rotation of different types of stars is an important scientific challenge. Fortunately stellar rotation is something that can even be measured directly from time dependent brightness: stars don’t have smooth surfaces, like our own Sun they are spotted with activity. When we observe them, this non-uniformity is reflected in the data  as a quasi-periodic variation in their brightness. However, the time dependent variability in the emission from spotted, rotating stars is often not perfectly periodic. Spots on the surface of stars have a tendency to move and disappear or appear. This means that fitting a straight forward sinusoidal model to the data is not very reliable – and fitting a full physical model is extremely complicated. This project will investigate machine learning approaches, starting with Gaussian Process Modelling, to extract stellar rotation periods in an automated way  using data from the Kepler satellite.

### Agriculture : optical and radar imagery for sustainable agriculture - Joe Fennell & Therese Cantwell
Sustainable development of the world’s food production and supply systems is essential for meeting the demands of an increasing global population. New and more accessible satellite imaging technology has huge potential for improving agricultural efficiency. Utilising the latest earth observation imaging platforms (ESA’s Sentinel missions and NASA’s LandSat) we will look at a range of uses and techniques for optical and radar imaging in agriculture.

### Astronomy : Building a workflow to deploy a radio astronomy calibration & imaging pipeline to the cloud - Eugene de Beste & Herbert Nguruwe. 
Reproducible scientific pipelines have historically been a challenge in most computationally focussed fields. The Common Workflow Language (CWL) is a standard for specifying and simplifying the process of executing scientific processing pipelines, while ensuring simplicity of use, portability and reproducibility. This project will focus on transforming an existing Python and Jupyter Notebook based pipeline for calibration and imaging of radio telescope data. Participants will complete a CWL-ified workflow in a Jupyter environment and execute it on the IDIA cloud.

##Shorcuts to Projects in IDIA
- Radio Source Detection and Classification : rsdc
- Image-based data mining to improve radiotherapy for cancer treatment : idmrct
- Machine Learning for extracting Stellar Rotation Periods from Kepler data: mlsprk
- optical and radar imagery for sustainable agriculture : orisa
- Building a workflow to deploy a radio astronomy calibration : cwl


## First step
 You have received your username and password for the IDIA cloud system. You are welcome to change you password by 
 ssh'ing to jedi's VM using the code/line below.
 ```
 ssh -XY username@jedi.idia.ac.za
 ```
 Upon successful login  you may change your password to the one that you are more comfortable. This you can do by 
 ```
 passwd
 ```
You may follow the instructions that follow in changing your password

You can also login to the JupyterLab using https://jedi.idia.ac.za  and use your username and password.

## Groups
All users  belong to a certain group and the 2 main groups are student or tutor groups:
#### student 
#### tutor 
The  other goups are classsifed at projects level
#### rsdc :  You belong to the rsdc goup
#### idmrct :  You belong to the idmrct goup
#### mlsprk :  You belong to the mlsprk goup
#### orisa :  You belong to the orisa goup
#### cwl :  You belong to the CWl goup

If you want to check/verify which group you belong to, ssh to the machine (`ssh -XY username@jedi.idia.ac.za`) and type `groups`, you will see all the groups you belong to.
