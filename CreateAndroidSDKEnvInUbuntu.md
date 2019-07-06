# Create android develop environment in ubuntu

## Download
Download android sdk tools from https://developer.android.google.cn/studio

## Unzip android sdk tools
Unzip android sdk tools, and set the path

## sdkmanager
sdkmanager --list --verbose, list all the package available to install

## install platforms
sdkmanager "platform-tools" "platforms;android-28"

## install build-tools
sdkmanager "platform-tools" "build-tools;28.0.3"
