# Tips
# Pre-work - Tips

Tips is a tip calculator application for iOS.

Submitted by: Julija Pettere

Time spent: 42 hours spent in total

## User Stories

The following **required** functionality is complete:
* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [x] Settings page to change the default tip percentage.
* [x] UI animations
* [x] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [x] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [x] Rounding up total bill, and divided bill values
- [x] Ability for user to split bill
- [x] Ability for user to enter number of people they would like to divide the bill amongst
- [x] International restaurant tip guide
- [x] color scheme
- [x] loading default tip percentage value from settings after leaving app for 10 minutes

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src= http://giphy.com/gifs/3o8dp1nLCcXB0HyENy title= tipWalkThrough2 width=318 alt= Tip WalkThrough />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

The biggest challenge I experienced was learing to work with NSuserdefaults and functions such as
viewDidAppear and viewDidLoad. While I had prior programming experience and did not experience a lot 
of trouble learning swift syntax, uderstanding the flow of the app and connecting that to how things
would load up on the app was the part I struggled with understanding the most. On top of just 
understanding the flow of these functions I needed to learn how to save and load values for a certain
period of time by accessing NSDate which I had never previously done before.

## License

    Copyright [2015] [Julija Pettere]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
