# BonusAssignment

To deploy a web application using Azure Static Web Apps, you can follow these detailed steps:
1. Prepare Your Accounts: Begin by ensuring that you have active accounts for both Azure and GitHub. If you don’t have these accounts, sign up for them to proceed.

2. Create a GitHub Repository: Navigate to GitHub and create a new repository using an available template tailored for static web applications. Within this repository, make sure to include an `index.html` file, as this will serve as your application's entry point.

3. Set Up the Static Web App in Azure: Log into the Azure portal, then locate and select the option to create a new Static Web App. During the creation process, you will be prompted to link this Static Web App to your GitHub repository. Ensure that you connect it to the correct repository where your `index.html` file is stored.

4. Configure Build Settings: After linking the repository, you’ll need to configure the build settings. This includes specifying the application location and any other settings required for the build process, such as output locations and framework specifics (if applicable).

5. Monitor the Deployment Process: Once the application is deployed, you should monitor the GitHub Actions workflow. This will provide real-time updates as the build process proceeds. Wait until the build is completed successfully to ensure your application is fully deployed.

