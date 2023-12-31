<img src="https://avatars2.githubusercontent.com/u/2810941?v=3&s=96" alt="Google Cloud Platform logo" title="Google Cloud Platform" align="right" height="120" width="120"/>

# Google Cloud Platform App Engine Samples

Welcome to the guide to deploying applications using Google App Engine on Google Cloud Platform. By using App Engine, you can easily manage and deploy your web applications without having to worry about complex infrastructure.

## Deployment Steps

Here are the simple steps to deploy your application:

1. **Prepare the Development Environment**
    Make sure you have installed [Google Cloud SDK](https://cloud.google.com/sdk) and have authenticated your Google Cloud account.

2. **Initial Project**
   Clone this repository
    ```
    git clone https://github.com/syanzzz/testing-app-engine
    ```
    
4. **Project Configuration**
    1. Setup your Google Cloud project using the following command:
    ```bash
    gcloud config set project PROJECT_NAME


## 1. Configure App Engine
Choose the App Engine environment that suits your application (standard or flexible). Configure the app.yaml file to define the environment and other configurations.

## 2. Deploy Application
Use the following command to deploy your application:
```
gcloud app deploy
```

# Main feature

1. Automatic Scalability: App Engine automatically handles increased load by adjusting the number of instances.
2. Monitoring and Logs: Monitor your application performance via Google Cloud Console and access logs for troubleshooting.
3. Easy Updates: Perform app updates easily using the gcloud app deploy command.
