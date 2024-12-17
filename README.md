# Uncommon HTML Errors

This repository demonstrates some uncommon errors that can occur in HTML, particularly focusing on the interaction between the `autofocus` attribute and JavaScript event handling, and the use of undefined events.

## Bug Description
The primary bug involves attempting to use a custom event ('mycustomevent') that is not a standard HTML5 event.  Also included is an example of misusing the `autofocus` attribute with JavaScript's `focus()` method, which can cause unpredictable behavior.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the console errors and unexpected behavior.

## Solution
The solution demonstrates how to correct these issues.
