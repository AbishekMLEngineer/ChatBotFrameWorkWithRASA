
## interactive_story_1
* restaurant_search{"location": "Delhi"}
    - slot{"location": "Delhi"}
    - check_location
    - slot{"location": "Delhi"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "0", "budgetmax": "300"}
    - slot{"budgetmax": "300"}
    - slot{"budgetmin": "0"}
    - verify_budget
    - slot{"budgetmin": 0}
    - slot{"budgetmax": 300}
    - slot{"budget_ok": true}
    - action_search_restaurants
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "cjkach.kac@gmail.com"}
    - slot{"emailid": "cjkach.kac@gmail.com"}
    - action_send_email
    - utter_goodbye
    - action_restart    