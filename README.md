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
     
## How I learned about Selenium IDE ##

Majorly from the official documentation on the website [https://www.selenium.dev/documentation/](https://www.selenium.dev/documentation/)


## Challenges ##


## What I would improve ##



