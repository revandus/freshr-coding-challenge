# Freshr Programming Challenge

Build a simple single page web application to send SMS message via the Nexmo API.

## Requirement

* Use **any language**, other than PHP, for the backend. The backend is responsible for two functions:

 * Return a **hard-coded API response** for a list of user names and telephone numbers. For example:
 ```json
[{"tel": "+17783194321", "name": "John Doe"}, {"tel": "+85264300268", "name": "Jane Roe"}]
```
 * An endpoint that takes a phone number and a string,
 then makes a request to the **Nexmo API** to send the string as a SMS message to the specified phone number.

* Use **AngularJS** to build the front end web app. Implement a search box where the
 user can search other users by name (no need to get complicated in the search
 logic, it is dealing with <10 records). The user can select a name from the list
 and input a message in a textbox. Make sure you implement a button so I can send
 the message to the server.

* Your project should have a **README file** stating any dependencies needed to run
 your project.

* Follow **style guide** (e.g. PEP 8 for Python) when coding. You may use tools
 such as jslint to check your code before committing.

## Tips

* You can create a free account on nexmo and add phone numbers as test users.
* Use a framework for the backend if you see fit.
* Persistent storage is not required.
* Pay attention to how you commit your code. You are expected to commit code in
  meaningful smaller portions and **write clear commit history**. Imagine that we
  will conduct a code review remotely.
* Pay attention to **code structure**, **comments**, and **variables naming**.
* **NO NEED** to spend time on tuning the color or aligning the UI elements.
* You are expected to spend 4~6 hours to finish this.
