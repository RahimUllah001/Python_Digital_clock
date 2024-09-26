Imports:

We import the Tkinter module (Tk, Label, etc.) for creating the GUI and datetime module to retrieve the current date and time.
date_time() Function:

This function fetches the current time and date using datetime.now().
It formats the time into hours, minutes, seconds, and AM/PM using the strftime() method.
Similarly, the date is formatted into day, month, year, and weekday.
The function updates the respective labels for displaying the time and date and calls itself every 200 milliseconds to keep the display updated.
Clock Window:

We create a Tk object (clock) that represents the main window.
The Label widgets are used to display the time and date elements, each styled with custom fonts, background, and text color.
place() method is used to position each label at a specific coordinate within the window.
