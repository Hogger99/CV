
## George Hancock

## Contact Details

Mobile: 07850 495170  
Email:  
Address: XXXX

## Summary
I am an ambitious and collaborative junior developer who enjoys working and learning across the full tech stack.  
Having recently completed the intensive 12 weeks of Makers Academy, I have grown from an interested amateur coder into a competent and confident junior developer.  
I am currently looking to take on a career in the tech scene of London, where I can further expand my knowledge in full stack development aswell as being open to learn other useful skills in business strategy and product / project management.

## Projects

| Name                         | Description                               | Tech/tools                                              |
| ---------------------------- |-------------------------------------------|---------------------------------------------------------|
| **Light Cycle**            | A javascript game based on Tron LightCycle | React, Javascript, jest, html, css                      |
| **Samdb** | A Sparse Associative Memory Database      | Python 3.9, Conda, pip, PyTest, SQL, PostgreSQL, Docker |

## Work Experience

**Kontexia Ltd** (Feb 2023 - to-date )  
_Junior Developer Work Experience_

I am developing and documenting test routines for important components of a Python based library that is used in a Sparse Associative Memory Database system.
This system learns the sequences of generalised representations of streamed data in an explainable way. It can be used to:  
- detect anomalies using similarity measures
- classify previously unseen data
- make multiple step predictions of a sequence 

Using Pytest I developed test routines for four submodules that use Symbolic Vector Architecture techniques to represent data concepts:
1. A Randomly Distributed Numeric (RDN) Encoder-Decoder
2. A Randomly Distributed Symbol RDS Encoder-decoder
3. A Sparse Distributed Representation (SDR) of a generalised memory
4. A Persistence layer using PostgreSQL

The RDN Encoder-Decoder is responsible for generating randomly distributed sparse bit patterns for numerical values.  
My tests needed to verify the following features:
1. The encoder generates bit patterns with a predictable sparsity, randomly picked from a given high dimensional space 
2. The bit patterns generated for two relatively "similar" numbers (such as 100 and 101) have an overlap inversely proportional to the difference
3. The Encoder-Decoder correctly decodes a given bit pattern to produce the original number
4. The ability to save and restore an RDN to a PostgreSQL database

The RDS Encoder-Decoder is responsible for generating randomly distributed sparse bit patterns for symbol (string) values.  
My tests needed to verify the following features:
1. The encoder generates bit patterns with a predictable sparsity, randomly picked from a given high dimensional space 
2. The bit patterns generated for two symbols were relatively "dissimilar" with minimal overlap
3. The Encoder-Decoder correctly decodes a given bit pattern to produce the original symbol
4. The ability to save and restore an RDS to a PostgreSQL database

The SDR is responsible for representing a generalised memory of data concepts as a sparse, high dimensional bit pattern 
My tests needed to verify three main features:
1. The ability to compare two SDRs by calculating the similarity (weighted overlap - ie the sum of the minimum of the shared bits) between the two randomly distributed bit patterns
2. The ability to merge two SDRs and produce a bit pattern with relatively strong weights for the common bits and weak weights for the uncommon bits
3. The ability to save and restore an SDR generalised memory to a Postgres database
 
To develop the tests for persistence I had to get familiar with using Docker and installing images to run PostgreSQL


**G H Music** (2019 - Sept 2020)
I was a self-employed music teacher focusing on piano, organ and theory exams. As part of my business,  
I am also the organist for several local churches in which run the Sunday mass music, play at weddings and funerals and organise yearly concerts.

## Education

#### Makers Academy (October 2022 - January 2023)

I successfully completed the Makers Academy 16 week programming course in which I learnt the fundamentals of programming using Ruby, Javascript and SQL.  
The course focused on Test-Driven-Development, the usage of version control tools such as Git and Ruby testing frameworks such as RSpec. 
In the final month I worked in a small team to develop a Javascript Game called Light Cycle. This game is loosely based on the Tron film in which two players race across a 2 dimensional landscape in  
which the objective is to kill the opponent with a light trail wall which cannot be crossed.  
I was responsible for the initial design and development in Javascript and React of the player motion and collision detection system within the game loop.  
My design needed to keep track of each player's current position as well as the history of their trajectories in order to implement collision detection.  
I used Canvas to update the DOM and plot the sprites in a performant way.  
As part of a team I participated in daily stand-ups to provide updates, discuss new ideas and to collaboratively help solve problems.  In addition, I served as scrum master on several occasions, checking progress and providing priorities  


#### The Royal Birmingham Conservatoire (September 2017 to June 2020)

I was awarded a full scholarship to study Organ as part of a four-year music degree. Due to the Covid pandemic,  
I decided to leave during the 3rd year and focus on my freelance music teaching business whilst I considered what career I wanted to pursue.  


#### Other Qualifications

Organ: Grade 8 Distinction
Piano: Grade 8 Distinction
Violin: Grade 7
Music Theory: Grade 5 Merit

Kings School Rochester:
Cambridge Pre-U: Music Distinction
A Level: Physics D
GCSE Level: Music A*, Maths A, English Language B, English Literature C, Physics B, Biology B, French B, Chemistry C, Religious Studies C  
Scholarships: Organ and Music
Awards: Full Colours for music December 2016

## Hobbies

I enjoy cooking, playing the organ, organising Dungeons and Dragons sessions, driving and socialising.

