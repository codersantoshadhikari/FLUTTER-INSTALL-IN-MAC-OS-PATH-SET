https://docs.flutter.dev/get-started/install/macos/mobile-ios
Open ~/.zshrc
Touch ~/.zshrc
export PATH="$PATH:/Users/santoshadhikari/developer/flutter/bin"
 --- Android studio Download
https://developer.android.com/studio

Xocode Install 

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

https://brew.sh

brew install cocoapods
 brew install cocoapods


homebrew install macbook m1

https://stackoverflow.com/questions/66666134/how-to-install-homebrew-on-m1-mac






----``````````````````````````````--------------````````````--------------------``````

1. Install Homebrew
Open your Terminal and run the following command to install Homebrew:

bash
Copy code
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
During the installation:

Follow the on-screen prompts.
Enter your macOS password if prompted.
Once installation is complete, add Homebrew to your shell profile by running the following commands:

bash
Copy code
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
Verify the installation by running:

bash
Copy code
brew --version
You should see the installed version of Homebrew.

2. Install CocoaPods
Once Homebrew is installed, use it to install cocoapods:

bash
Copy code
brew install cocoapods
3. Verify CocoaPods Installation
To confirm that CocoaPods is installed, run:

bash
Copy code
pod --version
This will display the installed version of CocoaPods.

