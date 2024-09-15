# expo-build

### 1. Install EAS CLI
First, you'll need to install the **EAS CLI** globally to manage your builds.

```bash
npm install -g eas-cli
```

### 2. Log in to Expo
Use your Expo account credentials to log in to the EAS CLI:

```bash
eas login
```

### 3. Configure the Build
Before starting the build process, configure your project for EAS by running the following command:

```bash
eas build:configure
```

### 4. Build the APK for Android
To generate an APK file (which can be installed directly on an Android device), use the following command:

```bash
eas build --platform android --profile preview
```
