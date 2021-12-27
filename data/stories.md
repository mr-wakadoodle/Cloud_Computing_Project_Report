## need help
* callpolice
  - utter_police
* callhospital
  - utter_hospital
* callfirestation
  - utter_firestation

## need help conversation
* greet
  - utter_greet
* needhelp
  - utter_how_can_i_help_you
* callpolice
  - utter_police
* callhospital
  - utter_hospital
* callfirestation
  - utter_firestation

## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_how_can_i_help_you

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
