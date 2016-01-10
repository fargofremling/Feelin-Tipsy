#Feellin’ Tipsy

Built by Alicia Fremling

*Feelin’ Tipsy* is a tip calculator application for iOS, it is optimize for use on iPhone 5(s), 6(s) and 6(s) Plus.

Time spent: #12 hours

#User Stories

Required: A user can enter a Bill Amount and see the Tip and Total values based upon tip percentage selected.

Required: A user is presented the decimal keyboard when the Bill Amount text field is activated.

Required: A user can change the Tip Percentage and sees Tip and Total updated respectively. (Options include: 15%, 20% and 25%)

Required: A user can dismiss the keyboard by tapping anywhere on the screen excluding the Bill Amount text field.

Optional: This application has an app icon added in all the dimensions required by Xcode. 

Optional: This application has a launch screen, which follows the iOS Human Interface Guidelines of “design(ing) a launch image that is identical to the first screen of the app”.

Optional: This applications includes on the app’s logo as an image asset. 

Additional: This application device orientation is limited to portrait  and upside down portrait to ensure optimal user experience. 

Additional: A user sees place holder content of $0.00 in the Bill Amount text field to prompt the entry of a dollar amount

Additional: A user is able to tap the clear button in the Bill Amount text field that appears while editing to easily delete its contents.

Additional: This application uses Auto Layout and Size Classes in order to use this app on all sizes of iPhones and iPads (see known issues). 

Additional: Updated four “var” functions to “let” since these functions were never mutated and resulted in a warning.

**Known Issues**

Auto Layout issue for iPhone 4s, iPad 2, iPad Air, iPad Air2 and iPad Retina - when the Bill Amount text field is active the keyboard covers part of the Total amount. 

When digits are entered into the Bill Amount text field, it is not formatted in standard two decimal  point currency formatting. 

#Demo GIFs

**User enters bill amount on the decimal keyboard.**

<img src='Enter%20Bill%20Amount.gif' title='Enter Bill Amount' width='' alt='User enters bill amount.'/>

**User changes the Tip Percentage and sees Tip and Total updated respectively.**

<img src='Change%20Tip%20Percentage.gif' title='Change Tip Percentage' width='' alt='User changes Tip Percentage.'/>

**User dismisses keyboard and app logo as image asset is revealed.**

<img src='Dismiss%20Keyboard.gif' title='Dismiss Keyboard' width='' alt='User dismisses keyboard and app logo is revealed.'/>

**User sees placeholder content in text field and is presented a clear content button when text is entered.**

<img src='Placeholder%20Text%20and%20Clear%20Content.gif' title='Placeholder Text & Clear Content' width='' alt='User sees placeholder content in text field and is presented a clear content button when text is entered.'/>

**User goes to homescreen to reveal app icon.**

<img src='App%20Icon.gif' title='App Icon' width='' alt='User goes to homescreen to reveal app icon.'/>

#License
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License.

You may obtain a copy of the License at: http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

See the License for the specific language governing permissions and limitations under the License.
