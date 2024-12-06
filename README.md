
## Continuous Deployment using AWS Code Pipeline and S3
# TL;DR
I hosted the code for my game on GitHub. To streamline the deployment process, I created an S3 bucket for static website hosting and set up a continuous deployment pipeline using AWS CodePipeline. This pipeline automatically deploys any changes to the code whenever updates are made.

# The Game
I created a simple memory matching game. The user clicks on two cards (each displaying meme images) in an attempt to match them. If the cards match, they disappear from the board; if not, they are flipped back over so the player can try again.

The game is built with HTML, CSS, and JavaScript.

Here are a few ideas for additional features I’m considering:

-> Adding a scoring system
-> Implementing a timer
-> Expanding the game with more cards
-> Introducing multi-player functionality to compare scores
-> The Deployment Environment
-> I decided to deploy and host the code on S3, using it for static website hosting.

# The Deployment Pipeline
I set up a continuous deployment pipeline with AWS CodePipeline. The pipeline pulls the latest code from my GitHub repository and automatically deploys it to S3 whenever there are changes.

# Cost
All of the AWS services I used are eligible for the AWS Free Tier. However, charges may apply after a certain usage threshold. I recommend shutting down resources when the tutorial is complete to avoid unnecessary charges.
