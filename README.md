# Clock-using-Python
🕒 Digital Clock using Python and Tkinter
This program is a simple Digital Clock application built using Python’s Tkinter GUI library. It dynamically displays the current time in a 12-hour format (including AM/PM) and updates every 200 milliseconds to keep the time accurate.

🔧 Key Features and Functionality:
GUI Interface: Built with Tkinter, the program opens a window titled "Digital Clock" with a stylized clock interface.

Live Time Display: Uses the time.strftime() function to fetch the current system time in the format HH:MM:SS AM/PM.

Auto-refreshing Clock: The time is refreshed continuously using the .after() method, which re-calls the get_time() function every 200 milliseconds.

Stylized Design: The clock uses custom fonts and colors (Arial, Calibri, with white text on a grey background) to enhance readability and aesthetics.

🧠 How it works:
A Tkinter window (master) is initialized and titled.

A static label is created for the title: "Digital Clock".

A dynamic label (clock) is used to show the current time.

The get_time() function retrieves and formats the time, updates the label, and schedules itself to run again after 200 ms.

mainloop() keeps the window running and responsive.

