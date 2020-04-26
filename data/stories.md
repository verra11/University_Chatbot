## happy path
* greet
  - utter_greet
  - utter_options
* college
  - utter_history
* thanks
  - utter_happy

## sad path 1
* greet
  - utter_greet
  - utter_options
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
  - utter_options
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
