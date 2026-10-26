# Short Project Report — Roamly Travel Planner

## Abstract
Roamly is a responsive web prototype for travel discovery and itinerary planning. It presents curated destination ideas, sample local guides, and an editable trip plan with estimated activity costs.

## Objective and scope
Travel-planning details are often spread across multiple pages and notes. This prototype explores a single place to discover destinations, collect activity ideas, and estimate trip spending. The original Scrum plan is preserved in travel-tourism-scrum-overview.html.

## Implementation
The site is a single static HTML document with responsive CSS and client-side JavaScript. It includes destination cards, destination search feedback, itinerary add/remove actions, localStorage persistence, budget totals, and sample guide profile dialogs. No server or live travel API is used.

## Demonstration
Open index.html. Add a destination idea or custom activity and estimated cost. Observe the activity count and total change, remove an item to recalculate, open a sample guide profile, then reload to see this browser's saved itinerary.

## Scrum context
The supplied overview states six sprints, fourteen activities, 115 story points, and a 72-day plan. These are source-plan figures, not measured implementation results.

## Limitations and future work
Destination prices, ratings, photographs, and profiles are illustrative. Search does not query travel services. There is no authentication, collaborative storage, live availability, booking, messaging, or payment. Future work could add validated travel APIs, secure user accounts, shared trips, date-aware estimates, and accessibility/usability evaluation.

## Conclusion
Roamly demonstrates a front-end journey from destination inspiration to a cost-aware itinerary. It is suitable as an interactive concept demonstration and foundation for further engineering.
