# CEWiT AI Twitter Bot Example
Example code given for the CeWiT Ethical AI Bot Workshop


The Python code for this repository was taken from the Twitter example documents and altered slightly.

## Requirements for this exercise:
- A Twitter Developers account, with the associated API Key and API Key Secret, Access Token and Access Token Secret, and Bearer Token. The "user authentication" must be set up with OAuth 1.0a Authentication permissions for the app to to read, write, and send DMs. This can be accessed within the Developer Portal Dashboard at https://developer.twitter.com/en/portal/dashboard. From here, click on the settings icon for this project app. From the app settings, scroll down to the **User Authentication** and click on the Edit icon. From here, change the app permissions so that the app has permissions to read, write, and send DMs. Completing this step also requires you to add a redirect URL and a website URL, but I had no issues putting https://www.google.com for both of these answers. If you have a perosnal website, props to you, and feel free to add it as the website URL!
- An IDE that can run Python (I prefer VS Code)
- The library `requests_oauthlib`: This library is available for download through pip3, which you should have if you've worked with Python. To install this library, run the command `$ pip3 install requests_oauthlib`

Prior to running the code for this workshop, please set your API Key and API Key Secret as environmental variables in the following format:
in your terminal please set your environment variables by running the following lines of code.
`$ export 'CONSUMER_KEY'='<your_consumer_key>'
$ export 'CONSUMER_SECRET'='<your_consumer_secret>'`

