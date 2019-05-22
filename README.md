# template-react-native
Template for ReactNative with Typescript for IOS, Android and Web Development



Links to help process the code:

1. https://github.com/necolas/react-native-web/blob/master/docs/guides/client-side-rendering.md
2. https://facebook.github.io/react-native/blog/2018/05/07/using-typescript-with-react-native
3. https://facebook.github.io/react-native/docs/running-on-device

Note: ">" Means terminal command

Steps for first time use (After git cloning the repo):
After going inside the repo --using terminal command ("cd") <br />
0. run yarn --> (To install yarn -> https://yarnpkg.com/en/docs/install#mac-stable)

...........................................................

Starting at the root folder -> "templete-react-native"

** To Start the web development ** 
1. ">" cd packages/web
2. ">" yarn
3. ">" yarn build
4. ">" yarn start

Your project should work on http://localhost:3000/

...........................................................

Starting at the root folder -> "templete-react-native"

** To Start the app development <IOS> ** 
1. ">" cd packages/app
2. ">" yarn 
3. ">" rm -rf ios/build
4. ">" yarn ios -> Recommand: use Xcode --> (Error:https://stackoverflow.com/questions/39778607/error-running-react-native-app-from-terminal-ios)

You have to download watchman for wml -> https://facebook.github.io/watchman/docs/install.html

5. ">" npm install -g wml
6. ">" wml add ../common ./node_modules/@wow/common <br />
--> ? Source folder is an npm package, add `node_modules` to ignored folders? Y
7. ">" wml start 
8. ">" yarn start

...........................................................

Starting at the root folder -> "templete-react-native"

** To Start the app development <Andriod plug in device> ** 
1. ">" cd packages/app
2. ">" yarn
3. ">" yarn android 

You have to download watchman for wml -> https://facebook.github.io/watchman/docs/install.html


4. ">" npm install -g wml
5. ">" wml add ../common ./node_modules/@wow/common <br />
--> ? Source folder is an npm package, add `node_modules` to ignored folders? Y
6. ">" wml start 
7. ">" yarn start
