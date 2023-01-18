# REST API to serve/edit calendar events

The purpose of this component is to enable web based clients to manage calendar events (aka meetings).

A meeting consists of:
- owner
- start time
- end time
- name
- meeting room

Two meetings can't be placed in the same room at the same time.

The API should allow for:
- list all meetings a user (owner) has for a particular day
- list all meetings a user (owner) has ever had
- create a new meeting
- update an existing meeting
- delete a meeting

The API specification is for the candidate to decide, but it should follow the REST architectural style. 
Please provide basic documentation of it, so we can test. 
Please provide steps to run or deploy it on the internet.

The implementation should be done with Node.js or Python (Django, Flask, FastAPI).

Strongly recommended is to:
- use SQL database: MySQL, Postgres
- use Swagger for specification
