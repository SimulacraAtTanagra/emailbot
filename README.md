## The purpose of this project is as follows:
This is a container for the functions used in much of my email automation in Microsoft Outlook.
## Here's some back story on why I needed to build this:
After starting the remote working life during COVID, e-mail became the dominant mode of contact, putting additional pressure on individuals to not only respond to a problem or concern but also to respond signally receipt to alleviate anxieties. In this world, it's become more necessary than ever to have methods of managing this flow of data and this tool provides classification as an inroid into efficient management.
## This project leverages the following libraries:
pywin32, pandas, fuzzywuzzy
## In order to use this, you'll first need do the following:
If the user wants to use the folder move functions, they'll need structured data stored somewhere about individuals and destinations. Functions like `massmove` are looking for details like origin, destination, group affiliation and subject.
## The expected frequency for running this code is as follows:
Continuously