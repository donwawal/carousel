# carousel
CodePath Carousel Assignment

Time spent: [12] hours

Completed user stories:

Static photo tiles on the initial screen
 * [x] Optional: Photo tiles move with scrolling

Sign In
 * [x] Tapping on email/password reveals the keyboard and shifts the scrollview and Sign In button up.
 * [x] User sees an error alert when no email is present or no password is present.
 * [x] User sees a loading screen upon tapping the Sign In button.
 * [x] alertView.dismissWithClickedButtonIndex(0, animated: true) dismisses the loading screen with no buttons.
 * [x] User sees an error alert when entering the wrong email/password combination.
 * [x] User is taken to the tutorial screens upon entering the correct email/password combination.
 * [ ] Optional: When the keyboard is visible, if the user pulls down on the scrollview, it will dismiss the keyboard.
 * [x] Optional: On appear, scale the form up and fade it in.

Optional: Sign Up
 * [x] Optional: Tapping in the form reveals the keyboard and shifts the scrollview and "Create a Dropbox" button up.
 * [x] Optional: Tapping the Agree to Terms checkbox selects the checkbox.
 * [x] Optional: Tapping on Terms shows a webview with the terms.
 * [x] Optional: User is taken to the tutorial screens upon tapping the "Create a Dropbox" button.

Tutorial Screens
 * [x] User can page between the screens
 * [x] Optional: User can page between the screens with updated dots
 * [x] Optional: Upon reaching the 4th page, hide the dots and show the "Take Carousel for a Spin" button.

Image Timeline
 * [x] Display a scrollable view of images.
 * [x] User can tap on the conversations button to see the conversations screen (push).
 * [x] User can tap on the profile image to see the settings view (modal from below).

Settings
 * [x] User can dismiss the settings screen.
 * [x] User can log out

Optional: Learn more about Carousel
 * [x] Optional: Show the "Learn more about Carousel" button in the photo timeline.
 * [x] Optional: Tap the X to dismiss the banner
 * [x] Optional: Track the 3 events:
     * [x] View a photo full screen
     * [x] Swipe left and right
     * [x] Share a photo
 * [x] Optional: Upon completion of the events, mark them green.
 * [] Optional: When all events are completed, dismiss the banner.
 
Walkthrough of user stories:

![Video walkthrough](https://s3.amazonaws.com/jules-codepath/jules_carousel.gif)

Notes:
Sign In: When the keyboard is visible, I implemented a tap gesture recognizer to dismiss the keyboard instead of a pull on the scroll view.
Learn more about Carousel: When all events are completed, the banner is dismissed on ViewDidLoad (which is not immediate)
