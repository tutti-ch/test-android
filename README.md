Hello!

Consider this open API: https://jsonplaceholder.typicode.com/

Develop a simple Android app that does the following:
  1. show initially an input field where user can type an email address,
  2. show a "Go" button next to the input field, that continues to step 3 when pressed.
  3. validate the input and if the input is not an email address show an error message and stop.
  4. check if the email address is in the api's user base (hint: https://jsonplaceholder.typicode.com/users ) and if it's not show an error message and stop.
  5. since this is a known api user, save the email address so that it's automatically filled in the input field next time the user starts the app,
  6. get a list of albums for this user (hint: use the user's id with this endpoint: https://jsonplaceholder.typicode.com/albums )
  7. choose the first album from the returned list and show the album's title
  8. final step: display the first photo (full or thumbnail) of the chosen album.

Notes:
- no need to go fancy on material design guidelines, just keep the UI effort to a minimum,
- the app should complete the work after the "Go" button is pressed even if the device is rotated and the context is recreated,
- free choice of guidelines/frameworks/libraries to use: this choice should reflect what you consider to be the best practice.

What we're looking for:
- clean architecture, self-explanatory code,
- proper use of Android lifecycle and components,
- ability to execute a queue of network requests,
- usage of external libraries that should simplify the task.

Have fun!
the tutti.ch team
