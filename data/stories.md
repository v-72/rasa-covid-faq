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
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## coronavirus faq
* coronavirus_faq
  - utter_coronavirus_faq

## covid faq
* covid_faq
  - utter_covid_faq

## covid symptoms faq
* covid_symptoms_faq
  - utter_covid_symptoms_faq

## covid helpline
* covid_helpline
  - utter_covid_helpline