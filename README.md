# Pre-work - *Bill And Split*

**Bill And Split** is a tip calculator application for iOS.

Submitted by: **Parth Patel**

Time spent: **9** hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [x] User can select between tip percentages by tapping different values on the segmented control and the tip value is updated accordingly
NOTE: The Segmented control is hidden as the slider is replacing that functionality. The code is still there for segmented control but commented out.

The following **optional** features are implemented:

* [ ] UI animations
* [x] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [x] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [x] Used Auto Layout to keep same layout across multiple iOS devices.
- [x] Adeed a custom color scheme (works but commented out).
- [x] Added a tip splitting feature to split cost between a number of people (max. 100)
- [x] Added Dark Mode for user preference (including remembering the saved state of the dark/light mode)

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src="/Bill_and_Split_iOS_App.gif?raw=true" title='Video Walkthrough' width='450' alt='Video Walkthrough' />

GIF created with [Imgur](https://imgur.com).

## Notes

Describe any challenges encountered while building the app:

- While creating the app, I found Auto Layout to be the most challenging. Since I'm a beginner at creating iOS apps, it was a little tricky in the early phases of the development
to get the layout to be the correct across every iOS device using Auto Layout. The second most challenging factor was implementing the Dark Mode feature. It is easy for iOS 13+
to have the normal Dark Mode feature integrated into the iOS app however, I was aiming to get a custom theme (which I attempted and can be seen in the classes/code).
Apart from that, the logic and behavior of the app was fairly easy and saving the current state of the app values in UserDefaults was fun too!

## License

    Copyright 2021 Parth Patel

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
