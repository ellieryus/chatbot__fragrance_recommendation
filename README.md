#Fragrance Recommendation System#
This project is a part of Coding for Analytics Course in McGill University.
A Python-based interactive questionnaire system that helps users find their perfect fragrance based on personal preferences, occasion, and budget.

##Overview##
This system guides users through a series of questions to understand their fragrance preferences and provides personalized recommendations. 
The questionnaire adapts based on user responses, creating a tailored experience for both personal shopping and gift-giving scenarios.

##Features##
Adaptive Questionnaire: Questions change based on previous answers.
Dual Flow System: Separate paths for personal shopping vs. gift purchases.
Comprehensive Profiling: Covers personality, season, occasion, scent preferences, and budget.
Multiple Choice Support: Both single and multi-choice questions.
Profile Generation: Converts user responses into a clean, readable profile format.

##How It Works##
Question Flow:

###Basic Information###
* Name
* Gender preference (Women/Men/Unisex)
* Shopping target (Myself/Gift)

###Conditional Branching:###
* For Personal Shopping:
  Season preference (Spring/Summer or Fall/Winter)
  Occasion (Casual, Formal, Romantic, Party, Work)
  Scent preferences based on season + occasion combination

* For Gift Shopping:
  Recipient's personality type
  Personality-specific scent preferences

* Universal Questions
  Brand category preference
  Budget range (varies by brand category)

###Decision Tree Logic###
The questionnaire uses a sophisticated decision tree designed by my teammates: Maral and Rachelle that branches based on:
* Target audience (self vs. gift)
* Seasonal preferences (for personal shopping)
* Personality types (for gift shopping)
* Occasion context
* Brand category preferences

