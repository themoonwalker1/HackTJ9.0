# The Safe Space
![GitHub language](https://img.shields.io/github/languages/top/TheMoonWalker1/HackTJ9.0?color=FF6663)
![GitHub language count](https://img.shields.io/github/languages/count/TheMoonWalker1/HackTJ9.0?color=FEB144)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/TheMoonWalker1/HackTJ9.0?color=FAFD7B)
![GitHub repo size](https://img.shields.io/github/repo-size/TheMoonWalker1/HackTJ9.0?color=9EE09E)
![GitHub](https://img.shields.io/github/license/TheMoonWalker1/HackTJ9.0?color=9EC1CF)
![GitHub last commit](https://img.shields.io/github/last-commit/TheMoonWalker1/HackTJ9.0?color=CC99C9)

Github Repo for our the 2022 Hack TJ hackathon 

<p align="center">
  <a href="https://github.com/TheMoonWalker1/HackTJ9.0">
    <img src="https://verawoodhead.files.wordpress.com/2018/02/be-1362307_1920.png?w=640" alt="Logo">
  </a>

</p>
  
## Inspiration
The new found technologies created to help us have in many ways been detrimental to us, especially to our mental health. Experts say that we are know in a mental health crisis with a record high amount of people suffering from bad mental health. A compliment a day has been shown to significantly improve the mental health of most people, and especially those who suffer severe mental health problems from unrealistic pictures on social media to classmates or coworkers making fun of their looks and personality traits. Furthermore, when a person is feeling sad, a compliment is one of the best ways to bring some happiness into that moment for them.

## What it does
It analyzes facial emotions from a webcam and provides a suitable compliment based off of various factors from what day it is to how the person facial expression is.

## How we built it
We utilized python and Tensorflow to make the facial emotion detection model and deployed that model using Azure. 
We implemented a website utilizing Node.js
We used thesafespace.online website utilizing Domain.com.
We implemented Twilio by modifying their provided code samples and APIs.

Parts of this project has been adapted from code from Atul Balaji (https://bit.ly/3KPcENu).

## Challenges we ran into
We ran into a variety of challenges. The first challenge we ran into was that about a minute into the competition one of our teammates laptop's screen broke rendering his computer almost unusable. We had to come up with a creative solution taking a monitor and playing around with his computer's settings so that we could still compete. Another challenge was that we were unable to run Tensorflow in any hosting site and spent 1.5hrs looking for a site to host our 2nd part of the web app, but then we found Microsoft Azure. We were also unable to try to get the camera to work within the web app for quite sometime. Twilio was also very challenging as we thought we kept providing the wrong inputs to the API, but rather it was a limitation with the trial Twilio account we were provided making it impossible to text any other number than the one provided at the sign up page. Lastly, while we had all of the individual parts working, it was quite hard to get Python, Node.js, and Twilio to work with each other.

## Accomplishments that we're proud of
Firstly, we are proud that we were given the chance to make an impact on the world through our computer science skills. We believe that this product has the potential to change the lives people all around the world who are emotionally neglected. We are also proud of the fact that despite this being our first experience with building and training a TensorFlow Model, we were able to quickly research about it and implement it.

## What we learned
For one, as previously stated, none of us had experience with building and training TensorFlow models. As a result, this aspect of the project was a completely new and exciting experience for us. In addition, we also learned about how to use the Twilio API, which we had no prior experience with. Finally, we also learned about how to use Navigator to access a computer's webcam through the browser.

## What's next for The Safe Space
We want to implement some more features that help the daily lives of people with mental health problems, or those who just need a boost for their day. An example of these features would be adding detection for facial features and not just emotions. It would also extend to having a person to chat with from our team, on an almost 24/7 schedule for the sake of the customer's mental health. With these goals in mind, we wish to help bring change to the community one step at a time. 
