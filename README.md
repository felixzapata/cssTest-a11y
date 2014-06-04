# CSS Test for accessibility issues
A set of rules for test accessibility issues from the book [Apps For All: Coding Accessible Web Applicatios](https://shop.smashingmagazine.com/apps-for-all-coding-accessible-web-applications.html/).

If the _test_ fails, show a message.

## List of messages

- _Warning: this button doesn’t have a type attribute. Is it a submit, reset or just button?_
- _Warning: You are making an element look like a button here. Is it really a button?_
- _Warning: It looks like you are styling an element to be disabled here. Make sure it is disabled properly._
- _You are not providing enough information about what this button does. Please include some text within the button._
- _Warning: it looks like you are using sections like divs. Sections should each have a heading_
- _Warning: You appear to be linking to a principal navigation block. Make sure it has the navigation ARIA role_
- _Warning: When JavaScript is turned off, this should be a link and should go to the navigation landmark_
- _Warning: All links inside a tablist should be defined as tabs, using the tab ARIA role_
- _Warning: Each tabpanel should be identified with an id attribute_
- _Warning: Each tab should explicitly control a tabpanel using the aria-controls attribute_
- _Warning: For better support, you should include a politeness setting for your live region role using the aria-live attribute_
- _Warning: For better support, you should include a corresponding role for your aria-live politeness setting_

## Usage

Load the css file in your project and check the messages.
