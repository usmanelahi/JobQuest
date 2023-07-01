# What is JobQuest?

"Take control of your job search journey with the all-in-one mobile app. Bringing together job listings from top platforms like Indeed and LinkedIn, JobQuest app empowers you to explore, apply, and connect with employers seamlessly. Experience the convenience of browsing diverse job opportunities, customizing your applications, and submitting them directly through the app. Say goodbye to the hassle of switching between platforms and embrace a streamlined job search experience that puts the power of applying at your fingertips."

# How To Run?

- Clone the repository on your system.
- Add (if any) addtional dependencies are required, all the additional dependencies are listed below.
- Execute the following command by navigating into the project directory using the following command:

```
expo-cli start --tunnel
```

- In case the following error is displayed 'Dependencies are not compatible with currently installed expo package version when running npm start' while building the project, use:

```
expo update
```

It just means that some of the dependencies in your project are out of date and not compatible with the version of expo you are using in your project.

- The Metro bundle will start creating the app, then select the platform of your choice to run the JobQuest app.

# Additional Dependencies Installed

- ### Enable Expo Globally

```
npm install -g expo-cli
```

- ### Font

```
npm install expo-font axios react-native-dotenv
```

- In the file "\_layout.js", the fonts have been enabled from the dependency installed.
