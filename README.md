# FriendlIE

FriendlIE was created as an application to help students in IE University find like-minded people in order to form friendships and network. We do this by creating profiles for each student with their information (such as country of origin, languages and hobbies), and match these with other profiles already in the database. 

### Instalation 

Download the file Alpha_FriendlIE.ipynb and use a program that recognizes this file type (Google Colaboratory and Jupyter Notebook are recommended).

If you want to test the functions using an example group of students to match with, also download userdatabase.csv.

### Usage

The first two sections give you options to use a pre-existing database of profiles (particularly userdatabase.csv). The first method uses an 'upload widget' and the second requires the file path. 

The forth section creates the class 'Profile', which is used to store the information about each individual student. These include: name, username, password, age, bachelor, nationality, hobbies, languages spoken, among others. The class also includes functions to standardize all the user inputs, in order to minimze user error. Additionally, the class has a function where you can set your priorities (e.g. first priority is meeting people with the same nationality). 
