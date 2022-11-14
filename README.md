<img width="76" alt="Group 3 (6)" src="https://user-images.githubusercontent.com/15788919/200873446-14588674-d6bf-4b0b-912c-06d27c8ada4a.png">

# Introduction
In person voting is probably one of the most archaic process in modern times. First tons of ballots needs to be printed out and distributed. Then, voters needs to show up where they are registered on a specific day with a valid ID. They need to queue and isolate themselves. Volunteers needs to help, control and then they needs to manually counts and report. Finally, a central entity needs to consolidate and publish the results. 
There are so many frictions that despite the importance of voting, abstention is on the rise, jeopardizing the health of our democratic communities. 

In parrallel, the blockchain technology offers valuable core properties for implementing an e-voting solution, such as no trusted third party, transparency and fully protected data storage.

This project intends to build an open source decentralized voting application. 

[Updated DB schema](https://ondras.zarovi.cz/sql/demo/?keyword=BlockVote)
[Current prototype](https://www.figma.com/proto/pgmKVTWh4lNywE4llCZjB6/E-voting?node-id=459%3A9085&scaling=min-zoom&page-id=404%3A2&starting-point-node-id=456%3A8884)


# Disclaimer and scope
Even if blockchain solves some key components of an election, online voting also comes with its own set of challenges that needs to be overcome in order to offer a viable alternative to in person voting. 

We can group the remaining challenges in to groups: 

Community based challenges
- Accessibility: How to distribute voting tokens to all participants? 
- Resistance to coercion: How to we prevent any form of outsider interferences (i.e. intimidation, fraud, forced vote selling, etc.)
- Technology and internet for all: How not to discriminate against voters who cannot or will not have the right accesses? 

Application based challenges
- Usability: Is the application offered clear enough for everyone? 
- Confidentiality: Can we guarantee voters that their choice remains secret?

# Scope 
The initial intent of this project is to focus solely on application challenges.


# Project breakdown
For the time being, BlockVote can be split into 2 distinct projects

1. A front end web app covering the 3 basic needs of a basic election: (i) setting up a poll, (ii) casting votes and (iii) displaying the results. 
2. A smart contract wizard generating a unique code for every poll initiated based on the inserted settings. 

Both projects can be used together or separated based on every community need. 

# Contributing
First, thank you for considering contributing to BlockVote.
- If you are a front end developer, we need help to convert our prototype into an actual app 
- If you are a solidity developer, we need help to build our smart contract template
- If you are into APIs, we need help to sync both apps

Finally, if you don't have time to dedicate but you still have ideas you would like to share improvement suggestions, don't hesitate to raise a GitHub issue. 

# Resources
Front end app 
- Figma prototype
- Development Trello board 


# Credits
- [Vocdoni](https://vocdoni.app/) by Aragon.org
- "Analysis of Blockchain Solutions for E-Voting: A Systematic Literature Review" by Ali Benabdallah, Antoine Audras, Louis Coudert, Nour El Madhoun and Mohamad Badra

# License
BlockVote is MIT licensed.
