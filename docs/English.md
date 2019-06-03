# Run Shortcut

Run Shortcut lets you access all of your shortcuts from the Notification Center Shortcuts widget. Use your voice to run and edit shortcuts on your device, or trigger shortcuts to run on remote iOS devices using NoteCuts.

- [**Download Run Shortcut from RoutineHub**](https://routinehub.co/shortcut/2905)

![Run Shortcut](https://adamtow.github.io/run-shortcut/images/run-shortcut-hero.png)

## NoteCuts Integration

Run Shortcut can run shortcuts on your iOS device even when [NoteCuts](https://adamtow.github.io/notecuts/English) is running in the background, monitoring for triggering events to run shortcuts automatically. Simply use the **Run with NoteCuts** run mode after selecting a shortcut to run. It will be added to either a local or remote NoteCut for execution at the next NoteCut evaluation period.

****

<span id="installation"></span> 
## Installation
Run Shortcut is made up of two shortcuts:

- **Run Shortcut Settings**: The shortcut that you download. It configures settings for use with Run Shortcut. 
- **Run Shortcut**: the primary shortcut you will be using from  the Shortcuts Notification Center Widget. You install this from the Run Shortcut Settings shortcut. 

****

<span id="setup"></span> 
### Setup Assistant
After downloading and running Run Shorty Settings for the first time, you will configure the following options in the setup assistant. 

![Run Shortcut Setup #1](https://adamtow.github.io/run-shortcut/images/setup-1.png)

- **Language**: Run Shortcut is localized for English, but comes with machine-translated localizations for over 25 other languages. [Help make Run Shortcut better by improving its localization](#localization) strings. 
- **Shortcuts Cache**: Makes accessing all of your shortcuts from notification center fast. This process will take several seconds if you have hundreds of shortcuts installed on your device. 

![Run Shortcut Setup #2](https://adamtow.github.io/run-shortcut/images/setup-2.png)

- **Run Mode**: Choose between running the shortcut, editing it, adding it to a NoteCut, or displaying a dialog with all three choices.
- **Launch Action**: When launching Run Shortcut, you can dictate the shortcut you want to run immediately, enter it via text, or view all installed shortcuts.

![Run Shortcut Setup #3](https://adamtow.github.io/run-shortcut/images/setup-3.png)

- **Dictation Language**: Got a shortcut whose name is in a different language? Switch between dictation languages so you can always find your shortcuts with your voice.
> **NoteCuts Integration**: Ever wanted to run shortcuts automatically based on a web-triggering event? Or had the idea to run a shortcut on a remote iOS device? If so, NoteCuts is for you! Run Shortcut can send shortcut commands to local and remote NoteCuts, even while NoteCuts is running in the background. [Learn more on how to use Run Shortcut with NoteCuts here](#notecuts). 

![Run Shortcut Setup #4](https://adamtow.github.io/run-shortcut/images/setup-4.png)

- **Install the Run Shortcut Widget**: The final step in the install process is getting the Run Shortcut Widget shortcut itself. Run Shortcut Settings always contains the latest version of Run Shortcut. 

While that was a lot of configuration, you're done! Tap on the newly downloaded Run Shortcut and run it from the Shortcuts Home screen. 

****

<span id="search"></span> 
## Searching for Shortcuts

Depending on what you chose for the Launch Action, Run Shortcut will present the following interface to you:

- **Dictation**: Speak the name of a shortcut you want to run. If there's only one match, Run Shortcut will move to the Run Screen. Otherwise, a list of shortcuts matching your search string will be displayed. You can specify multiple searches at the same time by saying `new line` in between keywords. 
- **Text**: Type in part of the name of the shortcut you want to run. Separate keywords with new lines to perform multiple searches. 
- **Show All Shortcuts**: Displays all shortcuts installed on your device since the last Shortcuts List cache. 

> NOTE: In order to work quickly at retrieving and display search results, Run Shortcut keeps a cache of installed shortcuts on the device. If you frequently install or remove shortcuts, be sure to tap on the **Update Shortcut List** action from within Run Shortcut. 

![Pagination](https://adamtow.github.io/run-shortcut/images/pagination.png)

If there are more matches that can fit on a single screen, Run Shortcut will display next and previous buttons. If there are 4 or more pages, a Go to Page option will appear allowing you to jump directly to a page. 

****

<span id="notification-center"></span> 
### Notification Center Widget

When set to use Dictation, Run Shortcut enables you to search and run all your shortcuts straight from the iOS Notification Center Widget. This is a powerful way to access all of your shortcuts without having to go into the Shortcuts app every time. 

#### Adding the Shortcuts Notification Center Widget

If you don't have the Shortcuts Notification Center Widget visible from Notification Center, perform the following:

![Adding Run Shortcut to Notification Center](https://adamtow.github.io/run-shortcut/images/notification-center-widget.png)

1. Swipe down from the top of the screen. 
2. Swipe from left to right to bring up the Notification Center Widget Screen. 
3. Scroll to the bottom. 
4. Tap Edit. 
5. Tap the plus icon next to Shortcuts. 
6. Move the Shortcuts widget where you want it to appear in the list of Notification Center widgets. 
7. Tap Done

Once installed you can search for an run any shortcut simply by going to Notification Center and tapping Run Shortcut. Speak the name of the shortcut you want to run and you're off to the races! 

> NOTE: If you see an Unable to Load screen appear after tapping Run Shortcut, it means the Shortcuts Notification Center Widget ran out of memory while trying to load Run Shortcut. Run Shortcut has been tested to work on an iPhone 6s Plus, iPhone X and an iPad Pro 12.9" (2018). Adjust the number of search results to display we page from Run Shortcut Settings to see if that resolves the problem. 

If you chose Text as your primary search style, Notification Center will be dismissed and you will be taken to the Shortcuts app to type in your search request. Because of that, it is recommended to set your search style to Dictation. 

****

<span id="run-mode"></span> 
## Evaluating a Shortcut

Depending on what you chose for the Run Mode setting, Run Shortcut will perform the following action when you choose a shortcut:

![Run Menu](https://adamtow.github.io/run-shortcut/images/run-menu.png)

- **Run Shortcut**: The Shortcuts app will open and the selected shortcut will be launched. 
- **Run Using NoteCuts**: The selected shortcut will be added to a local or remote NoteCut for running during the next NoteCut evaluation period. [Learn more here](#notecuts). 
- **Edit Shortcut**: The shortcut will be opened in the Shortcuts app for editing. 

If you chose Ask When Run, a menu will appear allowing you to choose from the three options above. 

****

<span id="commands"></span> 
## Commands
TK

****

<span id="notecuts"></span> 
## NoteCuts
TK

****

<span id="settings"></span> 
## Settings
TK

****

<span id="localization"></span> 
## Localization
Run Shortcut is available in English, but the application is also supplied with auto-translated localized files for the supported dictation languages on iOS.

Since machine translation is never perfect, your help would come greatly in handy. If you are a native speaker of one of these languages, consider contributing to improving Run Shortcut's localization files.

You can use the Localization Helper shortcut to assist with localizing Run Shortcut into your language.

> [**Download Localization Helper from RoutineHub &raquo;**](https://routinehub.co/shortcut/1931)

- When the localization file is complete, submit a pull request on [the Run Shortcut GitHub page](https://github.com/adamtow/promptkit/tree/master/localization/).

You can also inspect the files for each supported language's language dictionary in the `localization/application`  and `localization/widget` directories. Help make Run Shortcut more accurate and more universal for all iOS users!

****

<span id="app-framework"></span>
## App Framework
Run Shortcut was developed using the [Shortcut App Framework](https://routinehub.co/shortcut/1510) approach to developing application-like shortcuts. This framework was also used to develop:

- [**Cronios**](https://routinehub.co/shortcut/1267): The shortcuts scheduler for iOS.
- [**NoteCuts**](https://routinehub.co/shortcut/2711): Run shortcuts automatically on local and remote iOS devices.
- [**GeoCuts**](https://routinehub.co/shortcut/1732): Run your shortcuts automatically based on location triggers.
- [**Inspector**](https://routinehub.co/shortcut/1106): View and modify objects at runtime in your shortcuts.
- [**LaunchCuts**](https://routinehub.co/shortcut/959): Folders and tags for your organizing and launching your shortcuts.
- [**WatchCuts**](https://routinehub.co/shortcut/1864): Trigger shortcuts on your iPhone and iPad using any of your iCloud-connected devices: iPhone, iPad, Mac, Apple Watch, or iCloud.com!
- [**PromptKit**](https://routinehub.co/shortcut/2583): An advanced dialog engine for shortcuts and iOS. 

Learn more how you can create your own [shortcut applications with App Framework here](https://tow.com/shortcuts/framework).

****

<span id="license"></span>
## License
Copyright © 2019 Adam Tow • tow.com • @atow

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

