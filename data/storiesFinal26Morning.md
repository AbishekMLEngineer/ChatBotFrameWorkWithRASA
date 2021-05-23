
## interactive_story_1
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
    - check_location
    - slot{"location": "pune"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - verify_budget
    - slot{"budgetmin": 300}
    - slot{"budgetmax": 700}
    - slot{"budget_ok": true}
    - action_search_restaurants
    - slot{"location": "pune"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abishek.kachroo@gmail.com"}
    - slot{"emailid": "abishek.kachroo@gmail.com"}
    - action_send_email
    - utter_goodbye
    - action_restart
