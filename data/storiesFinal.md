
## interactive_story_1
* restaurant_search
    - utter_ask_location
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "kotham"}
    - slot{"location": "kotham"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - utter_restart
* restaurant_search{"location": "Jalandhar"}
    - slot{"location": "Jalandhar"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "Jalandhar"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abishek.karoo@gmail.com"}
    - slot{"emailid": "abishek.karoo@gmail.com"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_2
* restaurant_search{"location": "Jammu"}
    - slot{"location": "Jammu"}
    - check_location
    - slot{"location": "Jammu"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "700", "budgetmax": "10000"}
    - slot{"budgetmax": "10000"}
    - slot{"budgetmin": "700"}
    - verify_budget
    - slot{"budgetmin": 700}
    - slot{"budgetmax": 10000}
    - slot{"budget_ok": true}
    - action_search_restaurants
    - slot{"location": "Jammu"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abishek.kacho@gmail.com"}
    - slot{"emailid": "abishek.kacho@gmail.com"}
    - action_send_email
    - utter_goodbye
    - action_restart
