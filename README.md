# FriendlIE

FriendlIE was created as an application to help students in IE University find like-minded people in order to form friendships and network. We do this by creating profiles for each student with their information (such as country of origin, languages and hobbies), and match these with other profiles already in the database. 

### Instalation 

Download the file Alpha_FriendlIE.ipynb and use a program that recognizes this file type (Google Colaboratory and Jupyter Notebook are recommended).

If you want to test the functions using an example group of students to match with, also download userdatabase.csv.

### Usage

The first two sections give you options to use a pre-existing database of profiles (particularly userdatabase.csv). The first method uses an 'upload widget' and the second requires the file path. 

The forth section creates the class 'Profile', which is used to store the information about each individual student. These include: name, username, password, age, bachelor, nationality, hobbies, languages spoken, among others. The class also includes functions to standardize all the user inputs, in order to minimze user error. Additionally, the class has a function where you can set your priorities (e.g. first priority is meeting people with the same nationality). 

When running the fith section, you will be able to either log in or sign up. When doing the latter, you will be prompted to create your profile and set your preferences. This cell automatically calls for sign-up (for the UX Test). In order to change into signin, simply change the function from sign_up to login_username and login_password. 

The subsequent sections perform a series of functions in order to find the user their matches. These are: give weight to the user's given preferences, convert user's profile into a hash table to add to the user database, search for similar profiles, refining the list of matches to better suit user, check for duplicates and a quicksort to find the most similar profiles from that refined list.

Finally, the last section has a function that presents the 3 best matches to the user. 
