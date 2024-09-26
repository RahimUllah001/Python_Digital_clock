Imports:

We import the Tkinter module (Tk, Label, etc.) for creating the GUI and datetime module to retrieve the current date and time.
date_time() Function:

This function fetches the current time and date using datetime.now().
It formats the time into hours, minutes, seconds, and AM/PM using the strftime() method.
Similarly, the date is formatted into day, month, year, and weekday.
The function updates the respective labels for displaying the time and date and calls itself every 200 milliseconds to keep the display updated.
