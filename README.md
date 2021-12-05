## Database-generation-for-allergens
This website and the database is developed considering the need of a common metadatabase that consolidates data from some existing databases on allergens with additional information from different reputed journals and databases added manually and data processed computationally.  There is no existing database or metadetabase of Allergens provide such a comprehensive database of allergen related information. Additional features and functionalities have been added to make it easy to read, access, analyse and further use the data.

The project uses PHP, MySQL, HTML, CSS and Bootstrap to develop a responsive user friendly web application.

## Functionalities

Functionalities included in the project are

1. filtering text for different fields.

This features allows users to display only limited data entries according to their selection of filters for different columns. Pattern matching instead of exact full text match is used, thus increasing the database usability.

2. Filtering fields according to starting characters.

This feature allows users to select a field and a letter from the drop-down menus to display only those data rows which have the particular field starting with the specific letter only.

3. Option to download the complete database

<!--[Go to main database page image to view the UI for these functionalities ](#main-database-page)-->

## Guide

Create a new folder in htdocs folder of xampp folder in your system. Download all the files from this repo and store these in this newly created folder.
Import the sql files from the folder 'SQL files' into PHPMyAdmin / import the csv files from the folder 'csv files' into PHPMyAdmin.

## Information sources
These files contain the data that has been created using information mainly from 4 different databases on allergens.

1. Comprehensive Protein Allergen Resource (COMPARE)

2.	AllergenOnline (FARRP Allergen Database)

3.	WHO/IUIS Allergen Nomenclature Database

4.	Allergome Database

Additionally the data from other reputed jounals and sources has been processed to make a comphrehensive database on allergens.

### Homepage
This page gives a brief introduction  about the generated database and also the motivation behind executing this project.

<!--![image](https://user-images.githubusercontent.com/66554341/120322161-bbea2500-c301-11eb-91f5-f1bde8aa94ad.png)-->

### About Database page
This page is included to describe about all the databases from which the information was collected to generate a completely new database.  It gives an overview about all the 6 databases that have been used to collect information for the project.

<!--![image](https://user-images.githubusercontent.com/66554341/120328283-4e8dc280-c308-11eb-8080-65cd56e545f9.png)-->

### About Columns page
This page gives an overview about all the columns that have been included in the database table.

<!--![image](https://user-images.githubusercontent.com/66554341/120328483-77ae5300-c308-11eb-8746-74ef77355e89.png)-->

### Main Database page
This is the main page of the website that which displays the complete database that has been created along with the added features of searching, sorting and downloading the database. 

<!--![image](https://user-images.githubusercontent.com/66554341/120328857-e095cb00-c308-11eb-8770-c76f8ccad30b.png)-->

### Database Table
This is a part of the main database page which displays the whole database that has been created and if the filters are applied to the database the tabel is displayed accordingly.

<!--![image](https://user-images.githubusercontent.com/66554341/120061514-466d2300-c07b-11eb-9c68-5f21969389db.png)-->

### Tutorial page
This page is a complete guide the user about the walkthrough of the website. This page contains all the information about the different functionalities included in the website. This also gives the user a gist about the whole project.

<!--![image](https://user-images.githubusercontent.com/66554341/120328926-f60af500-c308-11eb-9481-89df8bb2b9be.png)-->

### Disclaimer
_The data in this database is obtained from various reputed legitimate sources. We have taken reasonable care to ensure that, and to the best of our knowledge, material information contained herein is in accordance with the facts and contains no omission likely to affect its understanding. Please note that we make no assurance that the presented data is free from errors. We do not intend on making any representation or warranty, express or implied, as to the accuracy or completeness of this database and will not have any liability towards any other person resulting from your use of this data.The information contained herein may be subject to changes without prior notice. We do not accept any form of liability, neither legally nor financially, for loss (direct or indirect) caused by the understanding and/or use of this report or its content._
