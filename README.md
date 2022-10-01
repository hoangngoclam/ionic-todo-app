## How to Run

> Note: It's highly recommended to follow along with the [tutorial guide](https://ionicframework.com/docs/react/your-first-app), which goes into more depth, but this is the fastest way to run the app. 

0) Install Ionic if needed: `npm install -g @ionic/cli`.
1) Clone this repository.
2) In a terminal, change directory into the repo: `cd photo-gallery-capacitor-react`.
3) Install all packages: `npm install`.
4) Run on the web: `ionic serve`.
5) Run on iOS or Android: See [here](https://ionicframework.com/docs/building/running).

## Build for IOS

Make sure your machine have install xcode, and you also run in IOS
Step 1:
```
npm install @capacitor/cli @capacitor/core @capacitor/ios
```

Step 2:
```
npx cap init
```

Step 3:
```
npx cap add ios
```

Step 4:
```
npx cap open ios
```
