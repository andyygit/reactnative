# reactnative
React Native 0.60-RC

Dependencies:
  Node, react-native-cli, JDK, Python2, Android Studio
  
  https://facebook.github.io/react-native/docs/getting-started

Env vars:
  ANDROID_HOME
  JAVA_HOME

Paths:
  platform-tools:
    C:\Users\username\AppData\Local\Android\Sdk\platform-tools

After installation:
  file: local.properties:
     sdk.dir=C\:\\Users\\username\\AppData\\Local\\Android\\sdk

Eslint:
  npm install eslint --save-dev
  ./node_modules/.bin/eslint --init -> .eslintrc:
    "extends": ["eslint:recommended", "plugin:react/recommended"]
