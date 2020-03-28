# Office Simulator Slackbot
Office slack messages are the passive agressive post-its of the modern world. Do you miss the office life? You won't any more with this realistic office slack simulator.

## In action
We have spared no expense, simulating the most realistic office messages, so you are never really at ease!

<img src="https://s3.amazonaws.com/tholman.com/office-simulator/github-readme-assets/office-sim-1.png" width="500">
<img src="https://s3.amazonaws.com/tholman.com/office-simulator/github-readme-assets/office-sim-2.png" width="500">
<img src="https://s3.amazonaws.com/tholman.com/office-simulator/github-readme-assets/office-sim-3.png" width="500">
<img src="https://s3.amazonaws.com/tholman.com/office-simulator/github-readme-assets/office-sim-4.png" width="500">

**This is serious stuff**
- Complete Realism
- 100% vetted passive agression!
- And of course, it REMEMBERS!

<img src="https://s3.amazonaws.com/tholman.com/office-simulator/github-readme-assets/office-sim-5.png" width="500">

*... 5 days later:*

<img src="https://s3.amazonaws.com/tholman.com/office-simulator/github-readme-assets/office-sim-6.png" width="500">

**Lets see that again!**

<img src="https://s3.amazonaws.com/tholman.com/office-simulator/github-readme-assets/office-sim-7.png" width="500">

*... 8 days later:*

<img src="https://s3.amazonaws.com/tholman.com/office-simulator/github-readme-assets/office-sim-8.png" width="500">

## Installation

1. Firstly, you will need to create a new "bot" integration, in your slack [settings](http://my.slack.com/services/new/bot). Type a username `Office Simulator` and click "Add Bot Integration". 

2. Once the bot is created, you will be shown an `API token` ... copy this, we'll need it later.

3. Next, clone this project, or download it as a [ZIP](https://github.com/tholman/office-simulator/archive/master.zip) and extract it.

4. Open up `index.js` in the root directory, and add replace `SLACK_API_TOKEN` with your slack token. You can also change the channel from `general` to one of your other channels, if you wish.

5. Finally, run `npm install` and `npm start` in the project, and you should see the initial team building message.

## Something to add?

Please, add new messages for the slackbot, etc, to the `/data/actions.js` file... you can use the `%modifier%` to add custom random alterations, as well as the `reaction` key, to add custom reactions.

Submit a PR, and I'll check it out!

## Note

Office simulator only posts once or twice a day, so if it doesn't seem to be constantly going, its due to painstakingly accurate realism.

## License

The MIT License

Copyright (c) 2020 Tim Holman - http://tholman.com
