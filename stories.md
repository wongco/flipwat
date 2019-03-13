# Flash Card App (Flipwat)

## Front-End (View)

- React Native / React Navigator
- Stretch Goal - React(TypeScript) - Web App

## Back-End (Controller)

- Flask/Django
- RESTful API
- Stretch Goal - Add in GraphQL Endpoint

## Database (Model)

- MongoDB
- Redis

Flash Card App Story Requirements:

Individual Card

- Users can add a new card, edit a card, and delete as well (CRUD)
- Cards should have two sides - Question and Answer
- Cards should be flipped over when clicked

Card Set

- Add ability for users to go to next question
- Add ability for users to go back to prior card
- Add ability for cards to be shuffled
- Should display the total cards remaining (ex: 5/30 , currently on card 5 out of 30)

## Open Questions:

- MultiUser - All Card Sets Private? Public? or Both (Informs usefulness of Redis/Caching)
- User State - Keep current card history in state to keep track of progress, current card maybe with redux? (Hydrate from LocalStorage/AsyncStorage)

## Stretch Technologies:

- Oauth (Facebook/Google Login)
