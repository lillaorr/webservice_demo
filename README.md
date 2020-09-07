# Adaptive Qualtrics input

webservices_demo contains a file that can be by used to define embedded data in Qualtrics. In order to access the variables stored in the file:

* In your Qualtrics survey, open Survey Flow.
* Add a new element, and select Web Service. Place this element upstream of the point at which you plan to use the embedded data.
* In github, view the “raw” file containing the variables you want to load in Qualtrics.
* Copy the github URL into the Web Service URL box.
* Check that the Web Service Method set to GET, and do not add query parameters or a custom header.
* Next to the Web Service URL, click Test.
* Select the variables you wish to save as embedded data, and click Add Embedded Data.
