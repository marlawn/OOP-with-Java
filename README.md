# OOP-with-Java
Practiced object oriented programming in Java (IntelliJ) by making a tuition manager. Polymorphism is utilized and we override certain methods such as toString(), equals(), and compareTo(). Included test cases for the methods in a PDF document and a testbed main() in two classes. Lastly, generated a JavaDoc for all classses in the package.

### Functions of the program included the following:
* Adding a student to the roster where each student uniquely identified by profile (first name, last name, and DOB), major, and number of credits completed.
* Remove a student from the roster, given the student's profile.
* Display the roster sorted in three ways
  * by profile
  * by grade (determined by credits completed)
  * by majors
* Change a student's major, given the student profile and a new major code.
* List all the students registered with a specified school (i.e. list all students in SAS)

### Specified restrictions:
* Student cannot be under the age of 16
* DOB may not be invalid
* DOB may not be today or future date
* Major doesn't exist
* Student is in roster already
* Negative number of credits completed
* Cannot remove student not in roster
* When changing major, must be a valid major

### Uses following Java library classes:
* Scanner
* StringTokenizer
* Calendar
* DecimalFormat

