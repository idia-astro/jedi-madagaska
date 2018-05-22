## Health : Image-based data mining to improve radiotherapy for cancer treatment - Andrew Green. 

Radiotherapy is a treatment for cancer in which radiation is directed into the patient to kill cancerous cells. Unfortunately sometimes the treatment does not work. In this project we will use data from several radiotherapy treatments to try and correlate the radiation dose with, for example, survival/recurrence aiming to improve radiotherapy for future patients. The project will follow the whole process of image-based data mining, including the use of tools to perform image registration and analysis techniques to interrogate the data.

### The project
We will be analysing data from The Cancer Imaging Archive (TCIA). There are two datasets for us to use:

[HNSCC](https://wiki.cancerimagingarchive.net/display/DOI/Data+from+Head+and+Neck+Cancer+CT+Atlas) - a set of 215 images where patients have details of their radiotherapy treatment. Several outcomes are recorded, including locoregional failure and feeding tube insertion. I have done some preliminary analysis on this dataset, which we will be using as an example.

[HNPET](https://wiki.cancerimagingarchive.net/display/Public/Head-Neck-PET-CT) - a set of 298 images where patients had Positron Emission Tomography (PET) scans in addition to CT scans and radiotherapy. There are several recorded outcomes, including locoregional failure.

The project starts from a point at which I have extracted all CT images, dose distributions and some relevant structure masks. We then use python tools to perform rigid, affine and non-rigid image registration. We can test how good the registration is by looking at how closely the structure masks match after the registration (though I haven't).

After the image registration, we can apply the transformations to the dose distributions, and start to do image based data mining. I have tested some code to do this with an outcome being whether ot not a patient needed a feeding tube; we can mine any of the other outcomes available during the workshop. For some outcomes, we have a completely independent validation cohort, which will be useful.

There are many avenues for exploration that we can consider in this project, including improvements to the registration process, and more advanced statistical mining techniques. I hope that some avenues for investigation will be suggested by the students too!

### The team

| Name | Expertise/Study |
|------|-----------|
| Andrew Green | Project leader/tutor|
| Elinambinina Rajaonarifara | PhD in Epidemiology of HPV |
| Manoa ANDRIAMIRADO| MSc HEP & data science |
| Zhunaid Mohamed | BSc Computer Science |
| Lameck Amugongo | PhD Image Based Data Mining |

Students wanting to get in touch before we meet in Madagascar, my email is andrew DOT green-2 AT manchester.ac.uk. Alternatively, I'm on the JEDI-MadagaSKA Slack!
