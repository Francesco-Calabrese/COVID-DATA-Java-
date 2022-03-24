# COVID-DATA-Java-
Pulls COVID Data and displays it to a chart

Summary
-------

This program is written in Java and is a stand-alone executable file. The user selects a country and a date range to pull the COVID deaths and cases. That data will be displayed on a line graph for the user to view. The user can select an additional country to compare as well as select the daily change instead of the total count of cases/deaths. 


Usage
-------

The image below is the main screen of the program. There are three sections of this display: selection menu, information menu, and data menu. 

![image](https://user-images.githubusercontent.com/96243400/159921217-5dfc213e-7187-411e-b663-82f3452865d6.png)


The selection menu is composed of the compare menu and view menu. The compare menu allows the user to either select one country to view data on, or select another country to view data on. The view menu allows the user to view the total cases/deaths or the daily change of cases/deaths. 

The information menu displays information about the program, such as user actions and warning messages.

The data menu allows the user to select the data to submit. Starting from the left to the right is the clear data button, which clears the information menu and selected previous data. Next is the select country drop-down menu. The user can select the country to view via drop-down feature or begin typing the country name (countries start with capital letters). Next is the date range selection, the first is the starting date while the second is the ending date. The final item is the get data button, which submits the data.

![image](https://user-images.githubusercontent.com/96243400/159919999-5a2abba1-faa9-43ab-be17-8abfbb4139e1.png)


![image](https://user-images.githubusercontent.com/96243400/159919673-3361cd0c-6896-4d9e-8641-498e49b2d5b9.png)

If the user selects two countries to compare, and additional dialog box will appear for the user to select an additional country. The user should then close that dialog box and then click the get data button from the data selection menu to submit the data. 

![image](https://user-images.githubusercontent.com/96243400/159922122-3d3a4121-ea66-4570-9d5b-2a362ff4fb99.png)

Once all of the data is submitted, a progress bar will display and alert the user on the progress. Upon completion of data retrieval, two graphs will display. One will contain the deaths (left graph) and one will display the cases (right graph). If two countries were selected, there will be a legend to denote with country is represented by which line. The user can clear data from the main screen or update the data (country, second country, dates, view menu). Once the get data button is submitted subsequently, all previous data is removed.  



