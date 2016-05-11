# MEAN Period 6

#### 1. Explain the concept of Hybrid Mobile App Development

Hybrid apps are apps that run in a webview in every platform. 
The idea is that the code should support all platforms (Android, ios, Windows, Blackberry etc).
Since the code produced runs in a webview, which runs as a beowser, you can use HTML to form your content, and JavaScript for the logic that the app will use. Because of this, the apps can be tested in a simple browser.
The use of Phone Gap and Cordova makes all of this possible.

#### 2. Explain the Pros & Cons of using Hybrid Mobile App Development compared to Native App Development

Native apps:

Pros:
- Native apps have the ability to work with a device's built in features.
- Internet access is not necessary.
- Access to the system hardware and functionality is easier.

Cons:
- More expensive for the developer. Costs higher due to maintenance and updates, especially of the app is compatible with more than one type of device.
- The process of publishing your app in the app store can be troublesome.
- The final product only works with one kind of device.

Hybrid apps:

Pros:
- The code will work on every device.
- Easier to maintain.
- Uses JavaScript and HTML.

Cons:
- Performance issues.

#### 3. Explain about the "building blocks" involved in an ionic Hybrid Application

1. AngularJS for presentation layer.
2. Cordova for communication with phone hardware.
3. HTML5 & Sass for styling and display of components.
4. ADB to communicate with phone and enables debugging.
5. Node.js to bring it all together.

#### 4. Explain and demonstrate ways to debug Hybrid Mobile Applications Running on a real device

With Ionic you can debug your app through your browser using the sockets and ports that the phone uses to communicate with the browser, this enbables you to see the console and debug live.

If you use: "ionic run android".

Open Chrome and navigate to: "chrome://inspect/#devices".

#### 5. Explain when and why CORS is a problem for Hybrid Mobile Applications

#### 6. Explain how and why it is possible for a Hybrid Application to access native phone devices like location, calendar etc.

#### 7. Explain using an example the "fundamentals" of an ionic application.

#### 8. Explain using an example how your Hybrid Application communicates with a backend and how CORS problems were solved (if any)


