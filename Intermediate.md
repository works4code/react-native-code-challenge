# Codezee-reddit React Native Coding Challenge

In this challenge you're going to create a basic Reddit app with React Native.

Reddit is a news website where registered users can submit posts or links to content that other users can vote and comment. Each of these posts is grouped into categories known as "subreddits".

Your web app should list the last posts of the r/pics subreddit.

To obtain the list of posts of a subreddit use the following URL:
https://api.reddit.com/r/pics/hot.json

For more information about the JSON structure see:
https://github.com/reddit/reddit/wiki/JSON 

## Requirements:

* Show a list of the posts in the r/pics subreddit.
* Display enough posts to fill then current viewport, then load additional posts as the user scrolls down on the page (infinite scrolling).
* Each post must show the following data: thumbnail image (if present), title, author, total number of votes (score), number of comments and date of creation.
* Example layout:

  ![image](https://user-images.githubusercontent.com/636075/44457253-08f22600-a603-11e8-9df2-6db2ea49b222.png)
* Once the user taps on a post navigate to the post’s URL in a WebView.
* A brief explanation of your design and assumptions along with your code.
* The app must run on iOS (bonus points for Android).
* You can use any existing boilerplate to bootstrap your app, or build your app from scratch. Keep in mind that the app must be easily executable from the command line.


How we review
-------------

Your application will be reviewed by our engineers. We do take into consideration your experience level.

**We value quality over feature-completeness**. 
The aspects of your code we will assess include:

* **Architecture**: how clean is the separation between the front-end and the back-end?
* **Clarity**: does the README clearly and concisely explains the problem and solution? Are technical tradeoffs explained?
* **Correctness**: does the application do what was asked? If there is anything missing, does the README explain why it is missing?
* **Code quality**: is the code simple, easy to understand, and maintainable?  Are there any code smells or other red flags? Does object-oriented code follows principles such as the single responsibility principle? Is the coding style consistent with the language's guidelines? Is it consistent throughout the codebase?
* **Security**: are there any obvious vulnerability?
* **Testing**: how thorough are the automated tests? Will they be difficult to change if the requirements of the application were to change? Are there some unit and some integration tests?
	* We're not looking for full coverage (given time constraint) but just trying to get a feel for your testing skills.
* **Technical choices**: do choices of libraries, databases, architecture etc. seem appropriate for the chosen application?

Bonus point (those items are optional):
* **Production-readiness**: does the code include monitoring? logging? proper error handling?

Submission
-------------

* Send us your code in a zip file or a link to info.codezee@gmail.com.

### Good luck!
