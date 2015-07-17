# How to Deploy on Google App Engine

Until now, you've been running your app on your laptop computer, which has been running a simple web server, and you've seen the results by browsing http://localhost:8080. That's great for writing and testing code, but at some point you'll want to run your app where other people can see it and use it. The process of uploading the components of your app to App Engine on the Google Cloud Platform is sometimes called deployment.

### Deploying Your App
You can deploy your app from App Engine Launcher. Follow these steps:

1. In the App Engine Launcher window, on the toolbar, click Deploy. (It’s on the right side, white arrow in a blue circle).  An authorization page will open in Chrome.
2. In the authorization page, click Accept. The page will change to tell you that authorization is completed.
3. Open the App Engine Launcher's Log Console. You can see the logging output about your app deployment process. When the uploading is done, you will see a message that says, "Completed update of app," followed by your project name and the app version, which in this case is 1.

### Finding and Sharing your App
Now you can see your app run in the cloud! To see your app in the browser, enter the following URL, replacing the placeholder text with your application ID (which you can find in your app.yaml file):

`https://<your-project-id>.appspot.com`

To see the other handlers run, just append the handler path like you did on your local computer. For example, to see the handler that is mapped to /results, use:

`https://<your-project-id>.appspot.com/results`

