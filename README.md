Run and deploy your Al Studio app

This contains everything you need to run your app locally.

View your app in Al Studio: https://ai.studio/apps/117d7c58-40c7-43e4-a840

-5a4e77b2ad1f

Run Locally

Prerequisites: Android Studio

1. Open Android Studio

2. Select Open and choose the directory containing this project

3.

Allow Android Studio to fix any incompatibilities as it imports the project.

4. Create a file named .env in the project directory and set GEMINI_API_KEY in that file to your Gemini API key (see env.example for an example)

5. Remove this line from the app's build.gradle.kts file: signingConfig = signingConfigs.getByName("debugConfig")

6. Run the app on an emulator or physical device

7. If you have already published your app in Al Studio, please request upload key reset in Google Play Console.
