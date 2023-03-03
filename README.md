# ZEBRA-DEMO

Zebra (née AUPM) is a package manager for jailbroken iOS devices, allowing you to install tweaks, themes, and other handy utilities not available through the App Store. Zebra uses the Advanced Packaging Tool (APT), originally developed by the Debian project.

This branch corresponds to Zebra 2, which is currently in active development. Zebra 2 supports iOS 14+ and macOS 11+. If you’re looking for Zebra 1, the current stable release which supports iOS 9 – 14, see the v1 branch.
How to Install

On iOS

The easiest way to install Zebra is to visit getzbra.com on your iOS device. This will guide you through the installation process.

Zebra requires a jailbroken iOS device. Jailbreaking is the process that gives you access to the tweaks, themes, and other tools you can install through Zebra. You can find out how to jailbreak at cfw.guide.

Zebra and jailbreaks are always free. Anyone suggesting you can install Zebra without a jailbreak, or accepting payment to download Zebra, is a scam. If you paid for Zebra or a jailbreak, contact your bank to file a chargeback.

On macOS

A stable release of Zebra for macOS isn’t yet available. You can build Zebra from source to try out the latest unfinished state of Zebra on macOS. You will need to install Procursus on your Mac, which is similar to Homebrew/MacPorts, but is based on the APT package management system Zebra is built for.

Downloads

You can also download Zebra directly via the GitHub releases if that is your fancy.

How to Build

If you want to compile Zebra yourself, you can use the following steps.

You’ll need a Mac with Xcode installed. To install on an iOS device, you’ll need Theos. To install on a macOS device, including the iOS Simulator, you’ll need Procursus.

Clone this repository using git clone --recursive https://github.com/zbrateam/Zebra.git

cd into the Zebra directory

If you want to build Zebra on macOS, open Zebra.xcworkspace, select Mac Catalyst, and click Run. You can also test the app on iOS by selecting an iOS simulator. This will pass through to the APT/dpkg installation on your Mac.

If you want to build Zebra to run on your iOS device, run make do.

Done!

Bug Reports & Feature Requests

Zebra tracks bugs and suggestions using the Discussions tab on our GitHub repo.

If you’re reporting a bug, fill out the required fields to the best of your ability in order to have a better chance of getting your issue fixed. We may require some additional information in order to isolate the issue in question and may ask for your response. Your help is appreciated.

Feature requests are welcome as well. Fill out the required fields to the best of your ability (mockups, screenshots, descriptions, etc.).

You must create a GitHub account to create a post. If you don’t have one, you can make one for free. You can alternatively email your bug report/feature request from within Zebra, or join our Discord server.

Pull Requests

Pull requests to fix bugs, add new features, and fix awful code (I’m sure there’s a lot) are very welcome. We’re here to help you if you get stuck while working on Zebra – please feel free to reach out to us on Discord if you want to discuss anything.

Translations

Zebra supports localization, but help is needed in order to translate Zebra!

If you are familiar with a language that is not currently supported by Zebra (you can check out a list of currently supported languages on Crowdin), you can help us out by translating Zebra into your language.

The easiest and preferred method is by using Crowdin.

If you want to add support for a new language to Zebra. First, file an issue here and tell us for which language you’d like to add support. Once we add it to Crowdin, you can start translating strings at https://translate.getzbra.com/
If you want to update a language already in Zebra and correct some issues, head over to https://translate.getzbra.com/, select your language, and update the new translations.
If there is a language that has an inaccurate translation that is already supported by Zebra, you can head over to CrowdIn and edit the string that has an issue directly from there. It will have to be re-approved in order for inclusion in Zebra.

New strings may be added in future Zebra versions from time to time, so it is important to keep a lookout for modified strings!

License & Credits

Licensed under the GNU General Public License, version 3.0. Refer to LICENSE.md.

Our header photo was taken by the San Diego Zoo. The Grevy’s zebra species is endangered, with an estimated population of 2,250 in the wild. Consider donating to the San Diego Zoo Wildlife Alliance to support their work in preserving these and other wildlife species.

Zebra was originally developed by Wilson Styres and Andrew Abosh.
