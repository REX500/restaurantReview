# Restaurant review dummy app

My first react-native app (how cute) built following an Egghead tutorial.

## Getting Started/ Installing

Clone the repo to your local machine.

In root folder of the project run
```
 yarn or npm install
```
 
Then navigate to `/server` folder and again:
```
yarn or npm install
```

This is because we have a dummy, simple and small node server in here too to aid with fetching list of restaurants and simulate adding a review.
If I'm feeling productive ill hook it up with MongoDb and actually enable you to add reviews... (Not for now as it's not the goal of learning RN)

### Prerequisites

Make sure you have these to make the app run:
* Have latest Node version installed: https://nodejs.org/en/
* Install expo cli from here: https://docs.expo.io/versions/latest/workflow/expo-cli/
* Install VS Code cause it's the best (for JS)

### Testing

No tests for now.

## Deployment

This project cannot be deployed on App Store/ Google Play for the followin reasons:
* main goal was to learn how react-native works - architecture, functions... This didn't include learning how to deploy
* I couldn't start the project with `react-native run-ios` after I added any type of navigation module - `react-native-navigation` or `react-navigation`. Both of these required me to run *pod install* which broke my project completely and threw a ton of Xcode related problems. I followed tutorials step by step with 0 luck. For that reason I decided to finish the project in Expo just so I can learn `react-native` and not worry about third party problems caused most likely by new versions or react-native, navigation modules, ios and/or xcode.
* if you feel like that last paragraph was a bit sarcastic and passive-aggressive that's because it was - I spent over 8 hours trying to debug these errors with 0 luck

## Built With

* [React Native](https://reactnative.dev/) - Framework used
* [Expo](https://expo.io) - Deploying React code on iOS/Android devices with ease

## Authors

* **Filip Malek** - *Initial work* - [REX500](https://github.com/REX500)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to Chris Achard for making an good but someplaces outdated Egghead tutorial @https://egghead.io/courses/build-a-react-native-application-for-ios-and-android-from-start-to-finish
