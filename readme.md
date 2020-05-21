Use the Fiddler tool
The free Fiddler tool can be used to capture the HTTP Requests sent by the remote component of your add-in to SharePoint.

There is a free extension to the tool that automatically decodes the access tokens in the requests.

After you have installed Fiddler on the web application server, add the following markup to your web.config file to make requests from your remote web app go through this proxy. This way, you can capture a Fiddler trace and see the full response from SharePoint when you get an error.
