# Medical Appointments NoShow Dataset Investiagtion

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

You will need the standard data science libraries found in the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.  

You will also want to download [nltk](https://www.nltk.org/data.html) - directions for this can be found in the text processing portion of the workbook.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in analyzing data from Brazilian medical facility which is about medical appointments with no show or show records. .  Specifically, I looked at the following questions:

- Is the status show/no show get effected by the patient's age ?
- Is the status show/no show related to the patient's gender ?
- Does the patient's with scholarships are more encouraged to show up in their appointments ?
- Are patients with handicap condition tend to show up or not ?  


## File Descriptions <a name="files"></a>

The following are the files available in this repository:

* `Investigate_a_Dataset.ipynb` - a notebook of the analysis performed following the CRISP-DM process.

* `noshowappointments-kagglev2-may-2016(1).csv` - csv containing medical appointments from kaggle, the description is inside the notebook. 

## Results<a name="results"></a>

1. Gender doesn't have a direct affect on the chances of a patient showing up or not.

2. Majority of Patients that don't show up are less than age of 40. On the contrary age groups of 40-60 and 60-80 are most likely to attend their appointments.

3. On contrary actually we would expect that patients who have got scholarship should have been all attended the physician but it seems that ~25% of patients did not attend.

4. The handicapped data is not enough to come up with a concrete relationship to the patient's appointment status.

In conclusion, the most likely factor to affect the patient's appointment status is the age variable. 

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to AirBnB and Kaggle for the data.  You can find the Licensing for the data and other descriptive information for the [Medical Appointments noShow on Kaggle](https://www.kaggle.com/joniarroba/noshowappointments).
