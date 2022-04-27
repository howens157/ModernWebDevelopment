Peter Davis, Hayden Owens

NOTE: If nothing shows up on the home page at first, please log out then log in again.


Peter's feature: Answer checking, unit tests for answer checking, updating stats from answer checking, only displaying clues that the user has not seen yet. In order to run the unit tests for answer submission, do npm i then npm test. The test/evaluate.js file includes the function which we have on Back4App as Parse Cloud Code.

Hayden's feature: Expanded auth module by creating a log out button and a forgot password feature using Parse functionality. Created a server in node.js that fetches a list of tweets using Twitter's API which we registered our app with. The app retrieves the data from the server and renders a twitter feed on the home page of the app full of jeopardy related tweets. Finally, created a share button on the home page that opens up twitter with a preformatted tweet for the user to invite their friends to try out the app. You can test the expanded auth module by creating an account and then logging out and clicking the forgot password link on the log in page, then entering the email you used to create your account. You will receive an email to reset your password and then can log in with the new password. The twitter functionalities can be tested by just loading the home page of the app. A twitter feed will slowly appear on the page that can be scrolled through as well as the share button that can be clicked to open twitter.

Note that the twitter feed does take a significant amount of time to load on the screen due to the amount of API calls required. If nothing is appearing, please wait a moment. Additionally, the console does show a significant amount of errors, but they are due to the twitter API we used, and not due to the code we have written.
