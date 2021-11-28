# setup RN dev env for mac

1. install homebrew

   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. install vscode

   ```bash
   brew install --cask visual-studio-code
   ```

3. install node.js

   ```bash
   brew install node
   node -v
   npm -v
   ```

4. install yarn

   ```bash
   brew install yarn
   yarn -v
   ```

5. install java8 JDK(android sdk)

   ```bash
   brew tap AdoptOpenJDK/openjdk
   brew install --cask adoptopenjdk8
   ```

6. add text to file /.zshrc

   ```bash
   export JAVA_HOME=/Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home
   ```

7. install Xcode (appstore)
8. install cocoapot

   ```bash
   sudo gem install cocoapods
   pod --version
   ```

9. install watchman

   ```bash
   brew install watchman
   watchman --version
   ```

10. install androidstudio(web)
11. add text to file /.zshrc

    ```bash
    export ANDROID_SDK_ROOT=$HOME/Library/Android/sdk
    export PATH=$PATH:$ANDROID_SDK_ROOT/emulator
    export PATH=$PATH:$ANDROID_SDK_ROOT/tools
    export PATH=$PATH:$ANDROID_SDK_ROOT/tools/bin
    export PATH=$PATH:$ANDROID_SDK_ROOT/platform-tools
    ```

12. install typescript
    ```bash
    npm i -g typescript ts-node
    ```
