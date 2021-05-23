## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Pune"}
    - slot{"location": "Pune"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "Pune"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "cjkach.kac@gmail.com"}
    - slot{"emailid": "cjkach.kac@gmail.com"}
    - action_send_email
    - utter_goodbye
    - action_restart


## interactive_story_22
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Jammu"}
    - slot{"location": "Jammu"}
    - check_location
    - slot{"location": "Jammu"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "Pune"}
    - utter_ask_email
    - utter_ask_emailid
* dont_send_email
    - utter_goodbye


## interactive_story_23
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Jammu"}
    - slot{"location": "Jammu"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "700", "budgetmax": "10000"}
    - slot{"budgetmax": "10000"}
    - slot{"budgetmin": "700"}
    - verify_budget
    - slot{"budgetmin": 700}
    - slot{"budgetmax": 10000}
    - slot{"budget_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "Pune"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abishek.kachroo@gmail.com"}
    - slot{"emailid": "abishek.kachroo@gmail.com"}
    - action_send_email
    - utter_goodbye
    - action_restart




## interactive_story_24
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Jammu"}
    - slot{"location": "Jammu"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "Pune"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abishek.kachroo@gmail.com"}
    - slot{"emailid": "abishek.kachroo@gmail.com"}
    - action_send_email
    - utter_goodbye
    - action_restart














