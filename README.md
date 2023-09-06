# coding-events-demo

You should write three sections. 
Purpose of the app. 
 - This application tracks events around diffrent locations and details about those events.

Current state of the app. 
 - The user is able to add events to application, and attach tags to the events.

Future improvements including your notes about the Person class.
 - We need to include a Person class in order to have users to select and save their favorite events.

Design:
Fields:
- Name - String
- Email - String
- Password - String
- List of Events - List<Event> (q.2) : ManyToMany ( q.3 relationships)
- Favorite Category - EventCategory(q.2) : ManyToOne ( q. 3 relationships)

Methods:
- Getters and Setters
- Get Back Favorite Events (returns all events that have to do with the favorite category)

