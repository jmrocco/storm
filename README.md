# Storm
Inspiration
Currently, there is a 2 BILLION dollar industry for smart speakers, and this is predicted to grow to 40 BILLION by 2020. Additionally, the market for voice to image generation technology is virtually untouched. In this fashion, Storm was inspired by the dream of transforming your own stories into movies with almost no effort!

A huge inspiration came from the VoiceFlow platform. This opened the doors for our team in terms of interacting with smart speakers and we were able to easily utilize their features and integrate with our custom API.

What it does
By engaging Storm on your Google Home and logging onto our web-app, you are free to tell any story and Storm will listen and produce images onto its UI based off of keywords detected. Storm is currently targetting children's stories as there is a clear demand for new and innovative story ideas. By eliminating the barrier of entry for teachers to develop their own storybooks, we allow them to fully utilize their creativities to create new stories.

How we built it
Storm uses complex Machine Learning pipelines, consisting of technologies from NLP to Image Recognition to statistical analyses to train a dataset capable of producing a flow of images identified from the text detected using a Google Home. The interface between the Google Home and Storm is handled by VoiceFlow and from there key phrases are passed to our data pipeline, where it is translated to images relevant to the story. Then, Storm displays the best-fit combination to its UI. However, at this point in development, every story must be inserted into our system a few days before use in order to allow the system to find the best-suited images.

Challenges we ran into
Almost half of our time was spent on brainstorming, therefore, development was rushed.

We came across a large delay in connecting our backend to the front (using WebSockets), consisting of errors with unsafe ports, CORS errors and many more. This involved translating the entire backend from Python to Node.

Spending too much time on Machine Learning development when the more important focus should have been creating a clean demonstration.

Accomplishments that we're proud of
Our UI was a top priority and we are very proud of its appealing, clean, functional design.

We are proud of our text detection hack built into VoiceFlow capable of identifying the data necessary for a unique demonstration.

What we learned
As first-time smart speaker application developers, everything was new territory.

What's next for Storm
A fully-fledged Machine Learning pipeline that can accept a range of words and descriptions and create appropriate photographs.

Increase the speed of our data generation so, ideally, it would be completed in real-time so teachers don't need to enter it prior.
