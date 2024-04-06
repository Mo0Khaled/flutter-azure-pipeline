# Flutter Azure DevOps Pipeline

This is a Flutter project that demonstrates how to build a Flutter app using Azure DevOps Pipeline.

we will build the following:

- Upload the Android app to Google Play Store
- Upload the Android app to App Center
- Upload the IOS app to TestFlight

Note: to upload the IOS app to appCenter, you need to copy the same steps as the Android app then change the appSlug that's it.

## Getting Started

- Add the azure-pipelines.yml file to the root of your Flutter project.
- Add the release.plist file to the ios/Runner/ folder of your Flutter project.

## Resources

Visit the following links to learn more about the tools used in this project:
- [Flutter Azure DevOps Pipeline Explanation Video](https://youtu.be/2GWrg2C5UDQ)

This is the flutter task extension that I used in the video to get the helper tasks for Flutter:
- [Flutter task extension](https://marketplace.visualstudio.com/items?itemName=Hey24sheep.flutter)

To increment the build number.
- [Rev.r](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/run-number?view=azure-devops&tabs=yaml#:~:text=number%20format%20is-,1.0.%24(Rev%3Ar),-%2C%20then%20the%20build)

This Get the last branch name.
- [SourceBranchName](https://learn.microsoft.com/en-us/azure/devops/pipelines/build/variables?view=azure-devops&tabs=yaml#:~:text=Build.SourceBranchName)

This Get the full branch path.
- [SourceBranch](https://learn.microsoft.com/en-us/azure/devops/pipelines/build/variables?view=azure-devops&tabs=yaml#:~:text=Yes-,Build.SourceBranch,-The%20branch%20of)

This will help you deploy to appCenter also for the app slug.
- [Deploy Azure DevOps Builds with App Center](https://learn.microsoft.com/en-us/appcenter/distribution/vsts-deploy)

This will guide you to create the server endpoint.
- [Create Server Endpoint](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/app-center-distribute-v3?view=azure-pipelines#:~:text=Inputs-,serverEndpoint,-%2D%20App%20Center)

This will help you create the provision profile.
- [Create a App Store provisioning profile](https://developer.apple.com/help/account/manage-profiles/create-an-app-store-provisioning-profile/)

This will help you add a secure file.
- [Add a secure file](https://learn.microsoft.com/en-us/azure/devops/pipelines/library/secure-files?view=azure-devops)

How to find and add variables.
- [Variables at azure](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/set-secret-variables?view=azure-devops&tabs=yaml%2Cbash)

A full walkthrough to create a p12 certificate.
- [p12 Generate Certificates](https://documentation.onesignal.com/docs/ios-p12-generate-certificates)


