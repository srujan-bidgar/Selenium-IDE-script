# Selenium-Script #

Using Selenium IDE to record automation to download the latest pdfs of judgments given by the Supreme Court on a date-to-date basis


## Why we use Selenium ##

- Selenium IDE allows users to record their interactions with a web application and replay them later. 
- Provides a simple interface for creating and editing test cases for testers who may not have extensive programming knowledge.
- It also allows users to edit and enhance recorded scripts using its scripting capabilities. 
- Supports multiple browsers such as Firefox and Chrome. Testers can record test cases in one browser and replay them in others.
- It provides features for debugging test cases, such as setting breakpoints, stepping through code, and inspecting variables. 
- Can export recorded test cases to Selenium WebDriver code (e.g., Java, Python, etc.), allowing testers to execute tests in different environments and integrate them into continuous integration workflows.

  

## How to use Selenium IDE ## 

1. Install Selenium IDE from the extension store of any web browser.
2. Identify and select a website that you'll use to access the PDF files from
3. Install Selenium Side runner on your local system:
   - Install selenium side runner module
       > npm install -g selenium-side-runner
   - Install a browser driver (for eg. firefox)
       > npm install -g geckodriver
4. Run the tests by calling the following command in your terminal
     > selenium-side-runner /path/to/your-project.side

     

## Snapshots of UI and working ##

<img src="https://github.com/srujan-bidgar/Selenium-IDE-script/blob/main/Screenshot%202024-03-04%20015323.png" width="822" height="400" />
<img src="https://github.com/srujan-bidgar/Selenium-IDE-script/blob/main/Screenshot%202024-03-04%20021003.png" width="822" height="400" />
<img src="https://github.com/srujan-bidgar/Selenium-IDE-script/blob/main/process-video.gif" width="822" height="400" />


## Process of accessing the pdfs ##



     
## How I learned about Selenium IDE ##

Majorly from the official documentation on the website [https://www.selenium.dev/documentation/](https://www.selenium.dev/documentation/) and some freely available tutorials on youtube




## Challenges ##
- [x] Figuring out how to input the right captcha every time - sending a text with ID of "cap"(captcha) and using the _storetext_ command to store it
- [x] Setting the date periods so that the latest pdfs can be accessed - by using a JS code to get the "to-date" as the latest date and "from-date" as 5 days prior to that date - code implemented using the    _executescript_ command
- [x] PDF opening in a new window/tab and hampering the recording for the script - writing JS code to access that element (of pdf to be downloaded) and setting its attribute to "download" - code implemented using the    _executescript_ command
- [x] Script failing to run because of slow website response or unavailibility of next response - by intorduicing a time delay using _wait for element visible_ command




## What I would improve ##

- [ ] Integration with more web browsers like Internet explorer, Brave,etc



