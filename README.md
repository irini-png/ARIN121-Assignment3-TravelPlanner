# ARIN121-Assignment3-TravelPlanner
AI Travel Planning Assistant
Overview
The AI Travel Planning Assistant is designed to help travellers create personalized travel itineraries based on their destinations, travel dates, budgets, interests, and preferences.
The assistant provides two main activities through an interactive menu: planning a new trip and revising an existing trip. It uses conversational interactions to collect information, generate recommendations, and adapt travel plans to the user's needs.
Features
1. Plan a New Trip
Users can create a personalized travel itinerary by providing information about their trip, including:
Destination
Trip duration
Number of travellers
Travel dates
Budget and personal interests
The assistant generates daily itineraries with suggested morning, afternoon, and evening activities. It also accommodates dietary requirements, recommends restaurants, provides travel maps and routes, and tracks estimated travel costs.
2. Revise an Existing Trip
Users can revise a previously created itinerary by explaining what they would like to change. For example, they may want to reduce walking, add indoor activities, change restaurant recommendations, or adjust their budget.
The assistant uses a guided, multi-turn revision process to:
Ask questions to collect any missing information.
Suggest adjustments based on the traveller's preferences.
Explain how proposed changes may affect the itinerary and budget.
Ask for feedback on the proposed adjustments.
Refine recommendations based on the traveller's responses.
Provide a complete revised itinerary once the traveller approves the changes.
The assistant preserves previously approved itinerary details that are not affected by the requested changes.
How to Use the Travel Planner
When beginning a conversation, users are presented with the following menu:
Plan a New Trip: Create a new personalized travel itinerary.
Revise an Existing Trip: Make changes to a previously created travel itinerary.
Users can select an activity by entering its menu number, activity name, or describing what they would like to do in their own words.
Once an activity is selected, the assistant follows the corresponding process:
For a new trip, users provide their travel information and preferences so the assistant can generate an itinerary.
For an existing trip, users provide their current itinerary and describe the changes they want. The assistant asks follow-up questions, suggests adjustments, and uses the user's feedback to refine the itinerary.
Users can switch between the two activities at any point during the conversation. The assistant carries forward relevant information already provided so users do not need to repeat themselves.
Project Structure
system-prompt.md: Contains the system instructions that define the assistant's purpose, menu, travel-planning activities, and conversational behaviour.
README.md: Provides an overview of the travel planner, its features, and instructions for using it.
