# Sauce Builder

Download all the required software from [here](https://saucelabs.com/downloads).
Right now, the automated testing is only supported in Firefox.
And for manual testing or scouting you can run from both firefox or chrome.


## Manual Testing

* Run Sauce-Connect for local hosted sites.
  * java -jar Sauce-Connect.jar [username] [api-key](https://saucelabs.com/account#)
* Please wait for "You may start your tests" to start your tests.
* Go to [Scout](https://saucelabs.com/scout) and enter the URL and select the browser.
* The browser should be opened, do the testing now.
* You can take screenshots by clicking 'Snapshot' on top-left of the page.
* If you find any bugs, 
  * please add them to the 'Bugs' task list on TeamBox and 
  * also click 'file bug' on the top menu
* Once you`re done with the testing, click 'Stop' on the top menu.


## Automated Testing

* This can be done through only firefox.
* Run Sauce-Connect for local hosted sites.
  * java -jar Sauce-Connect.jar [username] [api-key](https://saucelabs.com/account#)
* Please wait for "You may start your tests" to start your tests.
* Launch firefox and click Tools -> Launch Sauce Builder.
* Enter the URL in the text box, and click 'Go!'
* Then a new page with the url is loaded and it starts to record all your action on the page.
* Next, click stop recording.
* Click 'Run' -> 'Run on Sauce onDemand' and select the required browser and click 'Run'. 
* This will also 'Record a video' on the server.
* You can also add custom actions by clicking 'add new step above/below' when you hover mouse on the actions.
* TODO 



