
## interactive_story_1
* restaurant_search{"location": "kota"}
    - slot{"location": "kota"}
    - check_location
    - slot{"location": "kota"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "kota"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abi11@mai.co.in"}
    - slot{"emailid": "abi11@mai.co.in"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_2
    - utter_restart
* restaurant_search{"location": "London"}
    - slot{"location": "London"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - utter_restart
* restaurant_search{"location": "lofgs"}
    - slot{"location": "lofgs"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - action_restart

## interactive_story_3
    - utter_restart
* restaurant_search{"location": "jaipur"}
    - slot{"location": "jaipur"}
    - check_location
    - slot{"location": "jaipur"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "jaipur"}
    - utter_ask_email
* dont_send_email
    - utter_goodbye
    - action_restart

## interactive_story_4
    - utter_restart
* restaurant_search{"location": "aurangabad"}
    - slot{"location": "aurangabad"}
    - check_location
    - slot{"location": "aurangabad"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "aurangabad"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abish.kads@gma.com"}
    - slot{"emailid": "abish.kads@gma.com"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_5
* restaurant_search{"location": "shimla"}
    - slot{"location": "shimla"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - utter_restart
* restaurant_search{"location": "Amritsar"}
    - slot{"location": "Amritsar"}
    - check_location
    - slot{"location": "Amritsar"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "Amritsar"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abi11@maicx.com"}
    - slot{"emailid": "abi11@maicx.com"}
    - action_send_email
    - utter_goodbye
    - action_restart
