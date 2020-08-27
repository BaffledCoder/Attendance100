# Attendance100
Automation for scheduled zoom meetings.

### Features
* Automatically opens scheduled zoom meetings where schedule is saved in a csv file.
* Can send email notifications about meetings that have started and joined by the script.

### Setup (for Windows)
1. Download & Install Python from [here](https://www.python.org/ftp/python/3.8.5/python-3.8.5.exe).
1. Fill the zoom meeting links in ```timetable.csv```.
1. Enter the following paths in the batch file (```attendance100.bat```) -->
    ```"<PATH to python.exe>\python.exe" "<PATH to python script>\Attedance100.py" "<PATH to timetable file>\timetable.csv"``` without ```< >```(obviously).

### Notes
* ```timetable.csv``` column number 1 to 6 denote Monday to Saturday.
* Days where schedule is over early, should end with ```exit``` in ```timetable.csv```. (See timetable.csv for reference)

### Usage

Run ```attendance100.bat``` manually.

OR

**For complete automation** create ```New Task``` in ```Task Scheduler``` to schedule and run ```attendance100.bat```.

### Future
* Might update with more advanced features.
* Open to contributions & pull requests.
