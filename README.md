# Automation Testing (Selenium Tool)
## Overview of Automation Testing
### What is Automation Testing?
Automation testing is a technique uses an application to implement entire life cycle of the software in less time and provides efficiency and effectiveness to the testing software.

Automation testing is an Automatic technique where the tester writes scripts by own and uses suitable software to test the software. It is basically an automation process of a manual process. Like regression testing, Automation testing also used to test the application from load, performance and stress point of view.

In other word, Automation testing uses automation tools to write and execute test cases, no manual involvement is required while executing an automated test suite. Usually, testers write test scripts and test cases using the automation tool and then group into test suites.

The main goal of Automation testing is to increase the test efficiency and develop software value.

### Why Automation Testing is important?
<ul>
<li>Do automation testing at the time of lots of regression work</li>
<li>Automate your testing work when GUI is same but you have lot of often functional changes</li>
<li>Hight level testing - testing like a real user</li>
<li>Combinatorial testing</li>
</ul>

### What kinds of functions to automate using Automation testing tools?
Things to be automated are: 
<ul>
  <li>login forms</li>
  <li>registration forms</li>
  <li>the place where numbers of users access the Software simultaneously can be automated</li> 
  <li>all GUI items</li>
  <li>connections with databases</li>
  <li>field validations and</li> 
  <li>many-more can be efficiently tested automatically rather than manually</li>
</ul>

### Different Software testing tools Available in Automation Testing:
These are some tools which can be helpful in Automation testing:
<ul>
  <li>HP Quick Test Professional</li>
  <li>Selenium</li>
  <li>Visual Studio Test Professional</li>
  <li>WATIR</li>
  <li>IBM Rational Functional Tester</li>
  <li>TestComplete</li>
  <li>Testing Anywhere</li>
  <li>WinRunner</li>
  <li>LaodRunner</li>
  <li>SilkTest</li>
</ul>


## Introduction to Selenium
### What is Selenium?
Selenium is a free (open source) automated testing suite for web applications across different browsers and platforms. It is quite similar to HP Quick Test Pro (QTP now UFT) only that Selenium focuses on automating web-based applications. Testing done using Selenium tool is usually referred as Selenium Testing.

Selenium is not just a single tool but a suite of software's, each catering to different testing needs of an organization. It has four components.
<ul>
<li>Selenium Integrated Development Environment (IDE)</li>
<li>Selenium Remote Control (RC)</li>
<li>WebDriver</li>
<li>Selenium Grid</li>
</ul>

At the moment, Selenium RC and WebDriver are merged into a single framework to form Selenium 2. Selenium 1, by the way, refers to Selenium RC. 

### How to Choose the Right Selenium Tool for Your Need?
#### Selenium IDE
<ul>
<li>To learn about concepts on automated testing and Selenium, including:
  <ul>
    <li>Selenese commands such as type, open, clickAndWait, assert, verify, etc.</li>
    <li>Locators such as id, name, xpath, css selector, etc.</li>
    <li>Executing customized JavaScript code using runScript</li>
    <li>Exporting test cases in various formats.</li>
  </ul><li>
<li>To create tests with little or no prior knowledge in programming.</li>
<li>To create simple test cases and test suites that you can export later to RC or WebDriver.</li>
<li>To test a web application against Firefox only.</li>
</ul>

#### Selenium RC
<ul>
<li>To design a test using a more expressive language than Selenese</li>
<li>To run your test against different browsers (except HtmlUnit) on different operating systems.</li>
<li>To deploy your tests across multiple environments using Selenium Grid.</li>
<li>To test your application against a new browser that supports JavaScript.</li>
<li>To test web applications with complex AJAX-based scenarios.</li>
</ul>

#### WebDriver
<ul>
<li>To use a certain programming language in designing your test case.</li>
<li>To test applications that are rich in AJAX-based functionalities.</li>
<li>To execute tests on the HtmlUnit browser.</li>
<li>To create customized test results.</li>
</ul>

#### Selenium Grid
<ul>
<li>To run your Selenium RC scripts in multiple browsers and operating systems simultaneously.</li>
<li>To run a huge test suite, that needs to complete in the soonest time possible.</li>
</ul>

## How to Download & Install Selenium IDE for Firefox?
### Installation of Selenium IDE
#### What you need
<ul>
<li>Mozilla Firefox</li>
<li>Active Internet Connection</li>
</ul>

Selenium IDE Works with all major versions, but It is recommend to use 47.0.1 & above as they have better stability.
Selenium IDE is no longer compatible with Firefox 55 and above. 

#### Steps 1)
Launch Firefox and navigate to https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/. Click on Add to Firefox

#### Steps 2)
Wait until Firefox completes the download and then click "Install."

#### Steps 3)
Wait until the installation is completed. In the pop-up window, click "Restart Now."

#### Steps 4)
After Firefox has restarted, launch Selenium IDE using either of two ways:
<ul>
<li>By pressing Ctrl+Alt+S</li>
<li>By clicking on the Firefox menu button > Developer > Selenium IDE</li>
</ul>

#### Steps 5)
Selenium IDE launch

### Installation of Firebug
Firebug is a Firefox add-on that we will use to inspect the HTML elements of the web application under test. It will provide us the name of the element that our Selenese command would act upon.

#### Step 1
Use Firefox to navigate to Firebug's download page ( https://addons.mozilla.org/en-US/firefox/addon/firebug/)

#### Step 2
Wait for Firefox to complete downloading this add-on. On the dialog box that comes after, click "Install Now."

#### Step 3
Wait for the installation to complete. A notification will pop-up saying, "Firebug has been installed successfully." You can immediately close this pop-up.

<strong>Note:</strong> In case if you do not see above pop-up, no worries! This pop-up appears for a few seconds and disappears.
You do not need to restart Firefox after installing Firebug.

#### Step 4
Launch Firebug by doing either of these two methods:
<ul>
<li>Press F12</li>
<li>Click on the Firebug button in the upper right corner of the Firefox window.</li>
</ul>

#### Step 5
Firebug should launch at the bottom of Firefox.
<strong>Note:</strong> Firebug Extension is no longer under development and is deprecated as mentioned on firebug's site

It is Recommended using Firefox DevTools

You can access Firefox DevTools by using following steps
<ul>
<li>Open Firefox</li>
<li>Press Ctrl + Shift + "I"</li>
</ul>

<strong>Note:<strong> Advantage of using Firebug over DevTools is that, in FireBug, you can directly copy the XPath of a WebElement to be used in Selenium.
