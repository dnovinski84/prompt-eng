![GenI-banner](https://github.com/genilab-fau/genilab-fau.github.io/blob/8d6ab41403b853a273983e4c06a7e52229f43df5/images/genilab-banner.png?raw=true)

# {Using GenAI to Improve Requirements Gathering for a Study Bot}

How can Prompt Engineering improve the process of designing a study bot?

<!-- WHEN APPLICABLE, REMOVE THE COMMENT MARK AND COMPLETE
This is a response to the Assignment part of the COURSE.
-->

* Authors: [Danielle Novinski](http://www.YOURPAGE.xxx)
* Academic Supervisor: [Dr. Fernando Koch](http://www.fernandokoch.me)

  
# Research Question 

Exploring methods of using GenAI and Prompt Engineering to improve the requirements gathering process. 

## Arguments

#### What is already known about this topic

* It would be useful for a student to have a convenient and accessible study bot for self-practice and review.
* The design and implementation of such a bot is challenging due to the need to understand technology, the volume of information that needs to be included, and the need to ensure accuracy.
* Thorough requirements analysis is important when designing software. Proper scoping and consideration of all the requirements and design of the product will save time and money and lead to a quality end result. This is due to the fact that if changes are made during/after implementation has started, the rework can cause an increase in time and money spent.


#### What this research is exploring

<!-- Free-format; use the topics that are applicable to your exploration  -->

I seek to expand my knowledge of prompt engineering techniques using the references provided in the Prompt Engineering Lab.
I am using ChatGPT with a variety of prompts and questions for requirements analysis of a math study chatbot, and recording the different results.

#### Implications for practice

<!-- Free-format; use the topics that are applicable to your exploration  -->

Through this experiment, I will better understand the performance of various prompt engineering techniques.
The goal is to use prompting to produce a blueprint to design a math study chatbot. With this guidance, development could be conducted more accurately and efficiently. 
I also seek to understand more about the technology used in developing a chatbot.

# Research Method
I used the provided code examples to learn the structure of prompting and view the execution time of various techniques.
I manually entered questions and prompts into ChatGPT, experimenting with different phrasing.


<!-- WHEN APPLICABLE AND AVAILABLE -->

# Results

The experiment resulted in several robust prompts and answers from ChatGPT. The results included elements that I did not immediately think of, such as disability access and "personality" of the chatbot.

1. _I am a university student studying computer science. I have an assignment to create a Discord chatbot to help elementary students study math. Generate a prompt that will create a solution description for this chatbot._

ChatGPT's Prompt:
"Design a detailed solution description for a Discord chatbot that helps elementary school students study math. The solution should include:

Overview: A brief introduction explaining the chatbot’s purpose and target audience.
Features: Key functionalities, such as math quizzes, interactive games, hints, rewards, and difficulty levels.
Technical Implementation: The programming languages, frameworks, databases, and APIs used.
User Interaction Flow: How users will interact with the bot, including sample commands and response logic.
Security & Moderation: Measures to ensure a safe and appropriate learning environment for young users.
The description should be clear, structured, and easy to understand, keeping in mind the chatbot’s goal of making math fun and engaging for kids."

Result:
Here’s the solution description based on your prompt:

Math Buddy: A Discord Chatbot for Elementary Students
Overview
Math Buddy is a Discord chatbot designed to help elementary school students improve their math skills through interactive learning. The bot engages students with quizzes, games, and challenges that reinforce basic arithmetic concepts in a fun and encouraging way. The target audience includes young learners aged 6-12, parents, and teachers who want an accessible and interactive math learning tool.

Features
Math Quizzes & Practice

Covers addition, subtraction, multiplication, and division.
Supports different difficulty levels (Easy, Medium, Hard).
Provides step-by-step explanations for incorrect answers.
Interactive Games

Math Riddles: Engages critical thinking with fun word problems.
Number Guessing Game: Enhances number sense.
Flashcard Mode: Helps with quick recall of math facts.
Gamification & Rewards

Points and leaderboard system to encourage participation.
Achievement badges for completing challenges.
Daily math challenges to build consistent learning habits.
User Assistance & Engagement

Hints and step-by-step solutions to help struggling students.
Math facts and fun trivia to make learning more engaging.
Friendly feedback and encouragement to build confidence.
Technical Implementation
Programming Language: Python
Framework: discord.py (for Discord bot integration)
Database: SQLite or Firebase (for storing scores and progress)
APIs: Math APIs for generating additional problem sets
Hosting: Runs on cloud platforms like Replit, Heroku, or AWS Lambda
User Interaction Flow
User initiates a command (e.g., !quiz addition).
Bot presents a math question based on difficulty level.
User submits an answer.
Bot evaluates the response and provides feedback (correct, incorrect with explanation).
Bot updates the user's score and offers another question.
Leaderboards and rewards are updated accordingly.
Security & Moderation
Child-Friendly Responses: Filters inappropriate words and ensures positive interactions.
Limited Data Storage: Stores minimal user data for privacy compliance.
Parental & Teacher Controls: Admins can monitor and manage activity.
This chatbot ensures a safe, engaging, and educational experience for young learners, making math enjoyable through gamification and interactivity.

Would you like to add any specific requirements or adjustments? 

Next, I gave less context, but specified the technique.

2. _Help me create a prompt to design requirements for a math study chatbot. Use chain of thought technique._ 

ChatGPT's prompt:
Prompt for Defining Math Study Chatbot Requirements
We are designing an interactive math study chatbot for elementary school students. The goal is to create a user-friendly, engaging, and educational chatbot that helps students practice and understand fundamental math concepts.
Step 1: Define the Users
	• Who are the primary users?
		○ Age range: (e.g., 6-12 years old)
		○ Learning level: (e.g., basic arithmetic, fractions, word problems)
		○ Common challenges: (e.g., attention span, engagement, motivation)
Step 2: Core Functionalities
	• What features should the chatbot have?
		○ Should it generate math problems dynamically?
		○ Should it offer multiple-choice vs. open-ended answers?
		○ How will it handle wrong answers? Provide hints, step-by-step solutions, or explanations?
		○ Should it use gamification elements (e.g., points, badges, progress tracking)?
		○ Should it support voice interaction for younger kids?
		○ Can students ask the bot to explain concepts in simple terms?
Step 3: Personalization & Adaptability
	• Should the bot adapt based on the student’s skill level?
	• Will there be a difficulty progression system?
	• Should it keep track of performance history and suggest areas for improvement?
Step 4: User Interaction & Engagement
	• What kind of personality should the chatbot have? (e.g., friendly, encouraging, fun)
	• Should it use emojis, GIFs, or animations to engage students?
	• Will it allow students to compete or collaborate with friends?
Step 5: Technical Considerations
	• What platform will the chatbot be deployed on? (e.g., Discord, web app, mobile app)
	• What technology stack will be used? (e.g., Python, Node.js, AI integration for NLP)
	• How will it handle user input processing (e.g., spelling errors, natural language understanding)?
Step 6: Safety & Accessibility
	• How will we ensure a child-friendly and safe interaction?
	• Should there be content moderation to filter inappropriate language?
	• Will it be accessible for kids with disabilities (e.g., text-to-speech, dyslexia-friendly fonts)?
Step 7: Feedback & Continuous Improvement
	• Should students or parents provide feedback on chatbot responses?
	• Will there be error logging to improve the bot’s accuracy?
By addressing these step-by-step questions, we can define a clear set of requirements for our math study chatbot.

3. _Help me create a prompt to design requirements for a math study chatbot. Ask questions if needed._
   
Here’s a solid prompt to define the design requirements for your math study chatbot. Before finalizing it, I have a few questions to tailor it better:
	1. Target Age Group: Are the elementary students in a specific grade range (e.g., K-2, 3-5, or all grades)?
	2. Subjects Covered: Will the chatbot focus on basic arithmetic (addition, subtraction, multiplication, division) or include more topics (fractions, geometry, word problems, etc.)?
	3. Interaction Style: Should the chatbot use a quiz format, step-by-step explanations, hints, or gamified elements?
	4. Tone & Personality: Do you want the bot to have a friendly, encouraging personality or a more neutral, instructive one?
	5. Features: Should the bot provide explanations for wrong answers, track progress, or allow custom quizzes?
	6. Integration & Deployment: Will the bot be deployed on Discord only, or should it be adaptable for other platforms?
Once you clarify these, I can refine the prompt further!

In the first case, ChatGPT provided much of the design details. In the second and third cases, ChatGPT asked detailed questions and encouraged more user input in crafting a final prompt (and ultimately a solution description of a product). Based on my knowledge of the software development lifecycle, using the question-and-answer approach is a better method to refine the design to meet specific requirements and ensure a robust solution. 

I was unable to extend the code examples to try to generate prompts for the design of the math study chatbot or to build a bot capable of generating its own math study questions, however, this would be the next extension of the research.

# Further research

There is great opportunity with the question-and-answer method where the AI continues to ask the user questions throughout the process to further refine the response. This will allow features to be prioritized or ranked. In addition, the user can continue to prompt the AI to explain more about a certain area of design (tech stack for example). There is potential for this to be automated by constructing a dynamic query in the code. 
