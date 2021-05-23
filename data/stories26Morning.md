
## interactive_story_1
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "SomeGarbageCity"}
    - slot{"location": "SomeGarbageCity"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - utter_restart
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Jammu"}
    - slot{"location": "Jammu"}
    - check_location
    - slot{"location": "Jammu"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}    
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - verify_budget
    - slot{"budgetmin": 300}
    - slot{"budgetmax": 700}
    - slot{"budget_ok": true}
    - action_search_restaurants
    - slot{"location": "Jammu"}
    - utter_ask_email
* dont_send_email
    - utter_goodbye
    - action_restart
