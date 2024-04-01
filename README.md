# LinkedIn Network Expander

This is a Selenium IDE project aimed to be a bot for creating connections in LinkedIn.
Automates the action of connecting to users that match a certain criteria. 
This criteria is specified with the URL in which the user wants to send Connection invites to all the visible profiles.

## Installation

Download or install [Selenium IDE](https://www.selenium.dev/selenium-ide/). In my case I am using the [Chrome extension](https://chromewebstore.google.com/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd?pli=1).

## Usage

1. Run the application and select the `.side` file.
2. Open the test.
3. Replace the URL to be opened with yours.
4. Set the pages interval. This is the interval in which the bot will attempt to create as many connections as possible.
5. Run the test.

At the end of the test you should see how many connections have been made.

## Concerns

The automation and usage of this tool can led to issues according to [LinkedIn Bot Policy](https://www.linkedin.com/help/linkedin/answer/a1340567).
