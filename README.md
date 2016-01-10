**Feellin’ Tipsy**

Built by Alicia Fremling

*Feelin’ Tipsy* is a tip calculator application for iOS, it is optimize for use on iPhone 5(s), 6(s) and 6(s) Plus.

Time spent: ## hours

**User Stories**

Required: A user can enter a Bill Amount and see the Tip and Total values based upon tip percentage selected.

Required: A user is presented the decimal keyboard when the Bill Amount text field is activated.

Required: A user can change the Tip Percentage and see Tip and Total updated respectively. (Options include: 15%, 20% and 25%)

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
