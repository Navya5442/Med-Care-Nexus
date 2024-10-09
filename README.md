# Med-Care-Nexus
The project aims to develop a robust  data modelling solution for handling semi-structured data extracted from web pages of Hospitals. By utilizing ```MongoDB```, this project addresses the challenges of efficiently storing, querying, and managing heterogeneous data found across various web pages of Hospitals.

This model connects the hospitals enrolled in the website which facilitates to view  the details of patients , test reports etc...It deals with Medical Data which consists of data of various types which is multi-lingual and sensitive. This project proposes a Data Model for modeling medical data into a flexible format  which can be used for performing analysis in-order to take decisions for better health care systems.

## Software Requirements 
MongoDB<br/>
ReactJS, ExpressJS, NodeJS<br/>
Scrapy<br/>
## Hardware Requirements 
Processor – Core i3 or above<br/>
Hard Disk – 256 GB above<br/>
Memory   – 16GB<br/>
Stable Internet Connection<br/>
## Sample Webpages of the project
The following are the webpages that are designed for the project. Each webpage is designed to perform some specific functionality as mentioned below.

### ADMINISTRATOR’S PAGE

Only administrator will have access to this web page as the operations provided in this page will result in major changes in the document store. When doctor’s details of a particular hospital need to be added to the document store, the administrator will submit the URL of the hospital’s webpage which contains the details of their doctors. Then the details will be read from the HTML code of the webpage and added to the document store by the process called Web Scraping.

![image](https://github.com/user-attachments/assets/a72131a1-40bc-4115-b3ad-b0c0e8edabef)

### DOCTOR’S LOGIN

Details of the patients and hospitals are secured by providing authentication to the doctors which will avoid misuse of the data. Each doctor is given a unique ID with which he/she can login to the webpage and make changes to the patients details. If the submitted credentials are correct then he will be redirected to a page which provides patient’s details.

![image](https://github.com/user-attachments/assets/2665899f-656e-4ea6-b354-0287375687c8)

### VIEW PATIENT DETAILS

Now the doctor can get details of desired patients.
He can search for the patients with Patient ID / Patient name/ Hospital name .
The provided details are used to search for the documents in the collections stored in the database.
If the doctor provides Patient ID only 1 particular document will be displayed.
If he provides Patient name, all the details of patients with that name will be displayed.
If he provides hospital name, details of the patients of that particular hospital will be displayed.

![image](https://github.com/user-attachments/assets/f0b844ba-ccee-4f52-82c3-f3ea190716a8)

### DATA ENTRY

If a Patient is new to a hospital, a receptionist or a doctor can register the patient’s details. If the patient have already took some treatment from the hospital then a doctor or a lab incharge can upload the details of the test reports to the database. Depending upon the selection the user will be redirected to respective web page.

![image](https://github.com/user-attachments/assets/6ac2fefb-c59a-498d-aa28-53074e05da2a)

### REGISTRATION

This registration can be done by a receptionist or a doctor only. After registration, a unique patient ID will be given to the patient by the website. This ID can be used by the doctors, lab incharges or the patient as well for future purposes like uploading / viewing test reports.

![image](https://github.com/user-attachments/assets/c14c1526-47c9-4af1-ac68-34f004a51712)

### UPLOAD / VIEW TEST REPORTS

As it is complex to store the test reports in the form of text, the test reports are stored in the database in image format. These test report images can also be viewed / used by patient for further treatment. Only lab incharge and the doctor are allowed to use this webpage , so they are authenticated before allowing into the webpage.

![image](https://github.com/user-attachments/assets/aa0d0067-f268-432c-8275-d3a4b9cb20e2)

### A  INTERFACE TO THE PATIENTS

In this page, a patient can search for a doctor with respect to the specialization / hospital / location etc. He can also view his test reports by logging in with his unique patient ID and password. He can browse for the symptoms of a particular disease or can give details about symptoms of his illness to predict the disease.

![image](https://github.com/user-attachments/assets/e82fb386-8f51-4bb1-8244-f50dcd2ece30)
