# Implementation Plan

## Goal
Hvað ætlum við að fá virkt fyrst?

## Build order
    1. Prepare database
    2. Hosting a server
    3. Add basic HTML
    4. Login (add a user to the database)
    5. Let the developer add a game to be viewed by publisher
    6. Search functionability (which is just searching for stuff)
    7. Bulletin of games.
    8. Handling messages between the developer and publisher
    9. Test the user flow for both developer and publishers

## Dependencies
- Search function requires to view the profile´s role for results.
- User must have an account before able to both message and respond to them.

## Risks / open questions
- Handling huge quantity of data, especially in for loop will most likely cause problems
- wrong role assignment having missing data/wrong data
- Human oversight in the code (function that can break)

## First vertical slice
Raw data → data procesing → server data → bulletin board → game bulletin