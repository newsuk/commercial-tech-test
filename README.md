![](./src/invader.svg)

# Interview schedule

* Introduction.
* 30 minutes to complete the challenge.
* Review the challenge and other potential solutions.
* Questions.
* Wrap up.

# Welcome

* Please use any resources you would in your current ways of working.
* We don't expect you to know everything so if you copy anything from the web that's ok as long as you can explain what it's doing.
* We are looking at how you approach the challenge and how you come to a conclusion about what is required in the challenge. 
* Keep it simple, ask lots of questions to understand the challenge, and treat us as stake holders, or people you could pair with.
* There is no correct solution. We've seen so many different solutions.
* We're not looking for you to show us the most clever solution. Think simple, and iterate.
* Finally... Good luck 😄

# Setup

This is a basic install which will setup an environment that will output to the terminal. Jest is ready to use as per below when you're ready to start writing your unit tests.

1. Make sure you're using node v18.16.1 or greater. If you have `nvm` setup then feel free to run `nvm use`.
2. Run `npm i`
3. Run `npm start` - this will setup a watch task on `src/*.js`
4. When you're ready to tackle tests Jest is ready to run. Kill the watch task and run `npm run test:watch`

### Google Meet

Just in case you have issues with using screen sharing on Google meet

1. Follow these instructions to [give your mac permision to share](# macOS Guide: Screen Sharing With Google Meet)

2. Restart your browser, and re-join the meeting

# Challenge:

An out of this world civilization have landed on our planet and are occupying London, until now we have been unable to communicate with them.  

A linguistics professor has devised a simple sequencing language that will enable us to send them a message.  You and your partner have been tasked with writing an application which will power a row of 27 LEDs. to send a message to our new friends.

The application should be easily deployable, reliable and output a series of letters in the form of array to standard output with a 2 second delay in between each.  For now all we need you to send is the words:

"You are our friends."
