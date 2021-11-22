# Github Sponsors - Data Extraction
![cl8yxgdwgfiu14gu6nsg9rGold Lion Flat Illustrative Finance Product LogoSREZ](https://user-images.githubusercontent.com/94697656/142835920-8ead868d-db97-49a1-9585-dad43693a288.png)
## OBJECTIVE
The project's main aim is to extract data from the [GitHub Sponsors](https://github.com/sponsors/community) page and save it in the system neatly as a folder.

## MOTIVATION
The main motivation behind this project was to get a hands-on experience in web-scrapping. The amount of data that was to be scrapped was considerably large and just to get accustomed to such complex environments, this project was taken up. Also, working on projects involving scrapping and extraction, requires one to have phenomenal understanding of html codes and ways in which the information contained in them can be unsheathed. The very purpose of this project was to allow me to gain that understanding and expertise.  


## INTRODUCTION AND WORKING
The project requires certain information to be extracted from the. webpage stated above. To accomplish that, a plethora of functions and extraction strategies are used. Let's dive into more details.

The following information is extracted from the webpage:

1. Username of the developer.
3. A short description about their work.
4. Their full name.
5. No. of followers they have.
6. No. of people/organisations they follow.
7. No. of stars they have got.
8. Their location.
9. The no. of repositories they have.
10. No. of contributions they made last year.  

If any of the information is not available, then that field is marked as '-'.

All this inforormation is saved in a single file named 'Github Sponsors Data'. Not only this, for each developer/organisation, the data of the top repositories (names and their links) is also saved as a file, having its name as the username of the owner.

First of all, the above mentioned information is collected (the 10 points above). When all the information has been collected, the user gets notified with the output "Process Completed Successfully."  
The image below shows what exactly happens.  

<img width="301" alt="Screenshot 2021-11-22 at 7 03 44 PM" src="https://user-images.githubusercontent.com/94697656/142870707-e376dd66-cfae-497c-9461-9dbfc65922e2.png">  

The csv file generated at the end of this process : (It has been converted to .xlsx file for better viewing)  


<img width="1395" alt="Screenshot 2021-11-22 at 7 26 35 PM" src="https://user-images.githubusercontent.com/94697656/142874373-297e88f2-ba83-4ebb-a751-e5b56914704d.png">

Now, the data of the top repositories (names and their links) is collected for each user/organisation. When all the information has been collected, the user gets notified with the output "Process Completed Successfully."  
The image below shows what exactly happens.  

<img width="268" alt="Screenshot 2021-11-22 at 7 31 06 PM" src="https://user-images.githubusercontent.com/94697656/142875008-453b90a0-77a0-457e-b38e-eb76d71d612d.png">  

The csv files for a couple of developers/organisations is also shown below : (They been converted to .xlsx file for better viewing)  

### richfelker.csv
<img width="717" alt="Screenshot 2021-11-22 at 7 37 53 PM" src="https://user-images.githubusercontent.com/94697656/142875938-f9abd628-7db0-44d7-9486-c78169225e81.png">  

### phalcon.csv  
<img width="714" alt="Screenshot 2021-11-22 at 7 39 37 PM" src="https://user-images.githubusercontent.com/94697656/142876245-2f9550c9-6d1d-417d-a296-0f1dcd530bb0.png">

The folder 'Github_Sponsors' generated at the end of the execution conatains all this information about each developer/organisation along with the 'Github Sponsors Data' csv file. The contents of Github_Sponsors' has been shown below.

<img width="1122" alt="Screenshot 2021-11-22 at 7 43 22 PM" src="https://user-images.githubusercontent.com/94697656/142876870-a6604cdb-db74-4651-ae99-493d8dcb2d25.png">  

Do check the program code for detailed explanation of the code.

## FEATURES
1. Extracts a huge variety of data about each developer/organisation present in the [GitHub Sponsors](https://github.com/sponsors/community) page. 
2. Saves all the extracted data in the system neatly as csv files - in a folder with all the files named in it as per usernames.
3. Extracts data efficiently and covers all 'corner' cases of the different kinds of profiles present in the webpage so as to provide an impeccable performance.  

## TECH/FRAMEWORK USED
[Jupyter Notebook](https://jupyter.org/)

## CREDITS
This project was inspired by the following sources:
1. [Web Scrapping Project from scratch by Jovian](https://www.youtube.com/watch?v=RKsLLG-bzEY)
2. [Web scrapping project guide](https://jovian.ai/aakashns/python-web-scraping-project-guide)
3. [Scrapping with python🐍](https://medium.com/geekculture/a-gentle-introduction-to-web-data-extraction-scraping-with-e8dc7253b571)
4. [What is Data Extraction? A Python Guide to Real-World Datasets](https://towardsdatascience.com/what-is-data-extraction-python-review-of-json-xml-apis-sql-and-csv-formats-a5470afc27b6)








