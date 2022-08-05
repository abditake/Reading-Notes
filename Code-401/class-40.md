# [Class-41: React Native](/README.md)

## [getting started with react native](https://reactnative.dev/docs/getting-started)

## [expo](https://expo.dev/)

## [expo snack](https://snack.expo.dev/)

### [ejecting](https://docs.expo.dev/expokit/eject/?redirected)

<hr>


# getting started with react native

- Name three Core Components of React Native and describe what they do.
  - <View>: A container that supports layout with flexbox, style, some touch handling, and accessibility controls
  - <Text>:Displays, styles, and nests strings of text and even handles touch events
  - <Image>:Displays different types of images
- What problem does React Native solve (why call it native)?
  - You only need to maintain one codebase. although react native has issue with upkeep.
  - let you build your own components to suit your app needs
- What are the building blocks of a React Native app? How does that compare to a React app?
  - Text and view

# expo

- What solution does expo provide?
  - build a javaScript or TypeScript project that runs natievly on all users' devices
- Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.
  - managed workflow
- What is the difference between React Native and Expo?
  - If you've ever upgraded React Native or a native module you'll appreciate Expo's ability to seamlessly do this for you by only changing the version number.
  - Bare vs Managed workflow 

# expo snack

- Checkout this tool. What does snack allow you to do?
  - allows you to edit and test you app on browser.

# ejecting

- What does “eject” mean within the context of Expo?
  - being able to edit your projects with other IDE's such as xcode and android studios
- When should you not eject?
  - You enjoy the painless React Native upgrades that come with Expo. After your app is ejected, breaking changes in React Native will affect your project differently, and you may need to figure them out for your particular situation.
- Why might you choose to eject?
  - Your Expo project needs a native module that Expo doesn't currently support. We're always expanding the Expo SDK, so we hope this is never the case. But it happens, especially if your app has very specific and uncommon native demands. 
  - You are uncomfortable writing native code. Ejected apps will require you to manage Xcode and Android Studio projects. 