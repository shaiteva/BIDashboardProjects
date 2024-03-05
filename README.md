<h1>BI Dashboard Project
</h1>

<h2>Utilities Used</h2>

- <b>Pyton</b>
<br>Tkinter<br>
<br>Pandas<br>
<br>Matplotlib<br>

- <b>Excel</b>


<h2>Description</h2>

1. Daily and monthly reporting system for Gali shoe stores. (As it is the only store that has currently purchased the 
   application)

2. The system distinguishes between daily and monthly reports.

3. Store owners using this interface are required to input data into an Excel file according to sheets arranged by months 
   and to input the data added each day.

4. Daily report axis:
   
    a. Store owners are required to log in by typing the name of the shoe store and also clicking on the daily report 
       button. Store owners need to scroll through the months they want to select in order to receive the report and 
       additionally select a day in the month they want to receive information about. If the user enters a daily number that 
       is not listed in the respective month (according to the sheets in the file), it appears to the user that the day is 
       not listed in the system. If the user clicks the button without differentiation and does not enter a day at all, the 
       user is prompted to choose a day.
   
    b. When the user enters the correct month and day, what actually happens is that the selected month is taken from the 
       sheets in the file and the data is taken from the same day selected by the user, thus the relevant data is extracted 
       from an xlsx file and saved to a csv file.
   
    c. After the data is saved to a csv file, operations are performed using pandas for data filtering and other accounting 
       operations.
   
    d. After all those operations with pandas, the desired data appears in a window that activates two graphs within it.

<br />
