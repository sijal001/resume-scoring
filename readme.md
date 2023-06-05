


<h1 align="center"> <strong>Job Ranking</strong> </h1>


<p align="center">

<img src="https://img.freepik.com/free-vector/internship-job-training-illustration_23-2148751280.jpg" alt="Italian Trulli"  style="display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;">

</p>

<p> <strong>  Ranking resumes for a specific job description based on the matching content of both sides. !! </strong> </p>

---

## **Table of Contents**
Your section headers will be used to reference the location of the destination.

- [Description](#description)
- [How To Use](#how-to-use)
- [Repo Artitecture](#repo-artitecture)
- [Next Step](#next-step)
- [License](#license)
- [Author Info](#author-info)

---

## **Description**

<p align="justify">
  Ranking resumes for a specific job description based on the matching content of both sides.
</p>

<strong> Objectives </strong>

* Jupyter notebook or a plain Python file that reads the files 
* Writes another file with the indexes of the resumes 
* Writes specific ranking values.

<strong>Data Sources</strong>
<p align="justify">
There are three files:

1. <strong> job_description_response.json </strong> <br>
Contains the output of an automatic job openings search tool and has some structured fields in Json format.

2. <strong> resumes.csv </strong> <br>
contains 32 anonymized resumes' texts in a csv format. The names in the first column are form famous philosophers, and they must be present in your submission alongside with their respective positions in the ranking pool.

3. <strong> sample_submission.csv </strong> <br>
Contains a sample of how the output of your algorithm should be submitted. Please notice that the rank column does not contain the calculated similarity calculated, but the position of the resume among the others' ranks, being '1' the biggest match and 32 the smallest match. The numbers in rank column are integers from 1 to 32 and with no repetition.
</p>


<br/>

## **Technologies**
<br/>

| Library          | Used to                                        |
| ---------------- | :----------------------------------------------|
| Pandas           | To store and access info in a DataFrame        |
| sklearn       | To implement machine learning models and statistical modelling.                               |
| re           | To provides regular expression support        |
| jupyter          | To open Jupyter Notebook                       |



[**↥ Back To The Top**](#table-of-contents)

---

## **How To Use**

### **Installation** 

`Python Ver. '3.11.3'`

1. Open terminal `cmd`
2. Install the required libraries  `pip install -r requiement.txt`
3. Run file `profile_ranking.ipynb` for more details.
<br>


[**↥ Back To The Top**](#table-of-contents)

---

## **Repo Artitecture**
```
job_ranking
│───README.md                     :explains the project
│───requirements.txt              :packages to install to run the program
│───.gitignore                    :specifies files & directories to exclude from GitHub
│───profile_ranking.ipynb         :jupyternote book file that generates the output files.
│───analysis_test.ipynb           :jupyternote book file for testing the methodologies.  
│───result_ranking.csv            :csv file that contains final result /output.
└───data                          :director that contains all data files
    │
    |───job_description_response.json     :json file of the job requested.                        
    │───resume.csv                        :csv file that contains all the applicant csv.
    └───sample_submission.csv             :csv file that contains sample of output.
```

[**↥ Back To The Top**](#table-of-contents)

---

## **Next Step**

- Providing Ranking instead of scores.
- Improve data cleaning process along.
- Using Q/A model to improve the text processing and keyword extraction.
- Testing different model like Decission Tree, Recomendation, etc.


[**↥ Back To The Top**](#table-of-contents)

---
## **License**

Copyright (c) [2021] [Derrick Van Frausum, Joren Vervoort, Sijal Kumar Joshi]

<p align="justify">
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
</p>
<p align="justify">
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
</p>
<p align="justify">
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
</p>

[**↥ Back To The Top**](#table-of-contents)

---

## **Authors Info**

- Linkedin - [Sijal Kumar Joshi](https://www.linkedin.com/in/sijal-kumar-joshi-b1545584/)
- Github   - [Sijal Kumar Joshi](https://github.com/sijal001)

[**↥ Back To The Top**](#table-of-contents)
