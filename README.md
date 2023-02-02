# Lab-1_202001212
IT314 SE Lab-1

IT314 Lab-1

ID: 202001212
Name: Hemang Joshi
Date: 2nd February, 2023

Q1. Identify Functional Requirements and Non-functional Requirements.

**Functional Requirements:**
1. The Library Information System (LIS) should include the functionality of borrowing a book and returning it, along with a database where the details like borrowing date, last returning date, name and details of the borrower should be stored. The user should be able to browse through and search for books in this LIS.
2. For the borrower, LIS should include a feature of extending the borrowing duration, if the same book hasn’t been issued or requested by some other user.
3. In the LIS, the library staff should be provided with some additional privileges through which they can view details regarding books present in the library, books which have been borrowed, and the books which are due to be returned along with the borrower’s name. 
4. The librarian should be provided with admin access in the LIS so that he/she can control various aspects of the system. The librarian should be able to enter a new record for a book, and can also delete a record of an existing book.
5. For users who are not a part of the institute network, a view access of the whole catalog available in the LIS should be provided. They can view, search and browse through the books, but won’t be able to borrow them.

**Non-functional Requirements:**
1. *Portability:* The web application should be compatible on all different kinds of desktop browsers that support HTML 5 including some of the most used browsers like Google Chrome, Microsoft Edge, Safari, etc.
2. *Security:* The system should work only on the institute LAN. The passwords of each user should be encrypted and stored in a secured manner rather than stored as a plain text.
3. *Maintainability:* The system should not require much maintenance, and should not have any kinds of bugs in the interface.
4. *Usability:* The system should allow users from different backgrounds to use the LIS in an effortless manner and not hinder their experience in performing basic tasks.
5. *Data Manageability:* The librarian, who has been provided with the admin access, should only be allowed to have a direct access to all the data of the system, and no other user can alter the same. Along with that, the data should be stored in a manner that managing the same becomes easier.
6. *Availability:* The system should remain available almost 24 hours a day. If at all any downtime gets scheduled, it should be outside the working hours of the library.


Q2. Identify scope, features and non-functional aspects of the following problem.

**Scope**
The scope of the problem encompasses the people suffering from hearing loss and aims at delivering to them a low-latency real time application which notifies and makes them aware about the different kinds of sounds present in their surrounding environment. This would enable the user to remain aware about most of the activities going on in their surroundings.

**Features**
1. The application should use the microphone of the device to record all the different kinds of noise and sounds present in the user’s environment.
2. The application should be able to match a particular activity, person, or thing with the sound identified.
3. The application should be able to distinguish between different activities among the mix of sound inputs which it receives.
4. The application should have very low latency in notifying and alerting the user for the surrounding activities.
5. The system should be able to prioritize the alert or notification being provided to the user based on the activity determined by it. If some activity which requires an urgent action by the user, is happening, the application should provide a high priority notification which can include a full screen pop-up on the screen and a haptic vibration feedback.

**Non-functional aspects**
1. *Portability:* The application should be compatible with all the latest and most used versions of Android so that the maximum number of devices can use the application.
2. *Security:* The data of the surrounding environment of a particular user should be stored in a secured form in the application’s database, so that it can’t be easily accessed by anyone else.
3. *Reliability:* The system should not provide any false positives pertaining to the input of sounds it receives, should have a robust backend which is efficient and accurate enough to identify these sounds, and notify with a low-latency period.
4. *Usability:* The system should be user-friendly in its interface and not provide any hindrance to the user while interacting with the application. The system should be able to work without remaining connected to the internet.
5. *Maintainability:* The system should not have any bugs in the working of the application which might pose some difficulties to the user interface or the notifications being sent to the user.
