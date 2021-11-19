# RENKON CURRENCY CONVERTOR    
![8dwg8hryqrxfu1kwaej3dRenkon Currency Convertor Logo (1)SREZ](https://user-images.githubusercontent.com/94697656/142684036-8335f941-458e-413c-b343-e94ec663cd35.png)



## OBJECTIVE
The project's main aim is to extract data from the [website](https://www.xe.com/) of [XE](https://en.wikipedia.org/wiki/XE.com) and act as a tool for users that enables them to convert one currency to another and also give them a number of stats regarding the currencies entered as input.

## MOTIVATION
The motivation behind this project was to get a hands-on experience in data extraction and to furnish the skills of web-scrapping. The functionaity of the project : currency conversion,  was decided as the base to which the power of python libraries was added so as to create a potent tool that is more than just a currency convertor. The project was designed so as to aptly showcase both programming and data extraction skills.
## INTRODUCTION AND USING RENKON
>From here onwards, the project is referred to as **Renkon**.  

**Renkon** not only converts currency like any other currency convertor but it also provides additional stats and relevant data about the currencies entered. A detailed explanation is as follows.

On running, **Renkon** provides the user with a long table (> 172 rows) consisting of all the functional currencies and thier 3 lettered codes as follows:  

<img width="611" alt="Screenshot 2021-11-20 at 12 37 27 AM" src="https://user-images.githubusercontent.com/94697656/142678738-951b6c9b-72b1-4e1e-a232-0e9da2afdf2d.png">


Now, the user is asked to enter the code of the currency (referring to the table shown) which the user possesses, lets say the code is GBP for British Pound.  

<img width="534" alt="Screenshot 2021-11-20 at 12 39 35 AM" src="https://user-images.githubusercontent.com/94697656/142678797-6c6738b0-583e-49a9-ac57-7dc9c02d5207.png">


Then, the user is asked to enter the code of the currency that the user wants to convert his amount into, lets say its YER for Yemeni Rial.  


<img width="550" alt="Screenshot 2021-11-20 at 12 40 20 AM" src="https://user-images.githubusercontent.com/94697656/142679111-d30cc56b-b4be-4541-8cfb-c43faf9cf00a.png">  

The amount is then entered.  

<img width="532" alt="Screenshot 2021-11-20 at 12 41 03 AM" src="https://user-images.githubusercontent.com/94697656/142679272-203f4572-3125-4c41-af65-e78f24031cc3.png">  

Now the result is displayed by **Renkon** as well as the time and date of last updation of exchange rate is displayed as follows:  
<img width="843" alt="Screenshot 2021-11-20 at 12 41 58 AM" src="https://user-images.githubusercontent.com/94697656/142679399-2007e7cc-b6cc-4254-a28d-0e6a4bf87240.png">

Furthermore, the follwing the table is displayed:  

<img width="346" alt="Screenshot 2021-11-20 at 12 42 24 AM" src="https://user-images.githubusercontent.com/94697656/142679605-a81d0b60-c1c8-4111-bab5-26084e4bdb86.png">  

>Just to clarify  



|     Term      | Meaning |
| ------------- |:-------------:|
| High     | These are the highest points the exchange rate has been at in the last 30 and 90-day periods.   |
| Low      | These are the lowest points the exchange rate has been at in the last 30 and 90-day periods.    |
| Average      | These are the average exchange rates of these two currencies for the last 30 and 90 days.     |
| Volatility | These percentages show how much the exchange rate has fluctuated over the last 30 and 90-day periods. |  

Then, British Pound and Yemeni Rial stats are displayed.  

<img width="297" alt="Screenshot 2021-11-20 at 12 42 42 AM" src="https://user-images.githubusercontent.com/94697656/142680491-216cfb0f-d917-40b0-a623-081db1fefd8a.png">

Also, their profiles are displayed.

<img width="510" alt="Screenshot 2021-11-20 at 12 43 19 AM" src="https://user-images.githubusercontent.com/94697656/142680966-12415600-0d86-4d00-9434-84d7c6d46d4d.png">


In the end, **Renkon** asks whether one would like to continue or not and based on that **Renkon** gears up for one more conversion or exits.

<img width="522" alt="Screenshot 2021-11-20 at 12 44 03 AM" src="https://user-images.githubusercontent.com/94697656/142680792-7a1c899e-a4db-42a9-a009-a1882927d565.png">  

Do check the program code for detailed explanation of the code.

## Features
1. An efficient currency convertor that converters and works for over 172 currencies, including Bitcoin(XBT) and IMF Special Drawing Rights(XDR).
2. The exchange rates used are updated in real time, just seconds after the program runs.
3. The time and date of the updation of exchange rates is also displayed to showcase preciseness of data.
4. Based on the input, the High, Low, Average and Volatility stats are displayed for the last 30 and 90 days.
5. The stats of the currencies entered is displayed (as shown above).
6. Moreover the profiles of the currencies entered is also displayed (as shown above).
7. Extracts data effieciently and covers all 'corner' cases of different currency webpages of the website so as to provide an impeccable performance for all currency codes.

## Tech/Framework Used
[Jupyter Notebook](https://jupyter.org/)

## Credits
This project was inspired by the following sources:
1. [Web Scrapping Project from scratch by Jovian](https://www.youtube.com/watch?v=RKsLLG-bzEY)
2. [Web scrapping project guide](https://jovian.ai/aakashns/python-web-scraping-project-guide)
3. [Scrapping with python🐍](https://medium.com/geekculture/a-gentle-introduction-to-web-data-extraction-scraping-with-e8dc7253b571)




