# HackGT 2020
[Rohan Agarwal](https://github.com/roaga)\
[Arjun Verma](https://github.com/arjun11verma)\
[Anthony Wong](https://github.com/afxwong)
## Inspiration
It is clear to see that today's world is a fractured one. Even in this day and age where everyone can talk with virtually anyone, any meaningful conversation is rare. Instead, people turn to places like Twitter, Instagram, and Facebook as outlets for mudslinging and creating conflict, with society in a worse state than before they started. The effects of such a confrontational and close-minded society can be felt and have been for several years. Ever since the 2016 election, the nation has been on a downward spiral, almost to the point where it's nearly impossible to debate without a fight. With our application, we hope to revive what the forefathers valued so much: Civil Discussion.
## Solution
For us, this application is more than just a place people can talk about various topics. We want to fundamentally change the way people approach contentious issues. As firm believers in the idea that positive change only comes from constructive conversation, we have developed a platform that not only allows for telephone-style debates, but also transcribes and analyzes the conversation, creates text posts, and cultivates a space for meaningful, productive discussion.

First, if a user wants to have a discussion, they will sign into their account and search for the issue of their choice. They then can click the call button and wait for someone to match-up with. As they debate, their conversation is transcribed and arguments are analyzed and flagged if they are unsupported by evidence, claim a fact, or are opinionated/emotional. We were careful to consider psychology--this way, discourse always remains civil and productive, without bias or a disdain of being corrected. When the call ends, everything is automatically uploaded as a post for all to access and explore different, thorough perspectives on important issues.
## Technical Details and Challenges
We used React to create the entire front end, Firebase and Firestore for authentication and data storage, Google's Web Speech API for speech-to-text, Express.js and Socket.io for our real-time server, and our own original algorithm for live argument analysis.

All of us were relatively new to React, Express.js, and Socket.io, making this project challenging overall. The high quality presentation and the many features we strove for also added to the challenge. We had particular trouble with the nuances of converting speech-to-text data with traditional chatbox text into a single transcript with proper timing and accuracy. However, we pulled through with our own speech timing system, which also managed the timing of our flagging system.
## Accomplishments
As students who are cognizant of the things going on in the world around us, we know the country is becoming more and more divided by the day. We are happy that we took the opportunity to create something that could be the start of real change. We are also proud of the technical skills we have developed, the polished final product, and the experiences we have shared as a team.
## Next Steps
One major step we want to take is to make the generated content from debates more discoverable with a custom feed for each user. Another step is to allow more than two people in a call, allowing for a wider exchange of ideas in each discussion. We could also implement a business model; one possibility is to compensate users who record lengthy, high-quality debates and charge users for reading lots of transcripts, while another is to sell the software to schools and other organizations. To bring this to the real world, we would first approach classrooms and then move on to the general population.
## More Info
Check out our [presentation](https://docs.google.com/presentation/d/1Y-E6RSfOF1gD9ccM6naB9-8kxwzzS6Kg9dO3PM78KrQ/edit?usp=sharing) and our [video demo](https://youtu.be/ZNmO-JE_Suk).
