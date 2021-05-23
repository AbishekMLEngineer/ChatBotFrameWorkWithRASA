
## interactive_story_1
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "acjabc"}
    - slot{"location": "acjabc"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - utter_restart
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - check_location
    - slot{"location": "mumbai"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "mumbai"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abishek.kachroo@gmail.com"}
    - slot{"emailid": "abishek.kachroo@gmail.com"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_2
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - check_location
    - slot{"location": "delhi"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "delhi"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "ab111@mailinator.com"}
    - slot{"emailid": "ab111@mailinator.com"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_3
* restaurant_search{"location": "Amritsar"}
    - slot{"location": "Amritsar"}
    - check_location
    - slot{"location": "Amritsar"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "0", "budgetmax": "300"}
    - slot{"budgetmax": "300"}
    - slot{"budgetmin": "0"}
    - verify_budget
    - slot{"budgetmin": 0}
    - slot{"budgetmax": 300}
    - slot{"budget_ok": true}
    - action_search_restaurants
    - slot{"location": "Amritsar"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abi11@mail.co.in"}
    - slot{"emailid": "abi11@mail.co.in"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_4
* restaurant_search{"location": "Jalandhar"}
    - slot{"location": "Jalandhar"}
    - check_location
    - slot{"location": "Jalandhar"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "Jalandhar"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abi111@mail.co.in"}
    - slot{"emailid": "abi111@mail.co.in"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_5
* restaurant_search{"location": "Mumbai"}
    - slot{"location": "Mumbai"}
    - check_location
    - slot{"location": "Mumbai"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "Mumbai"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abi123.dfg@gmail.com"}
    - slot{"emailid": "abi123.dfg@gmail.com"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_6
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "ahemdabad"}
    - slot{"location": "ahemdabad"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - utter_restart
* restaurant_search{"location": "ajmer"}
    - slot{"location": "ajmer"}
    - check_location
    - slot{"location": "ajmer"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "ajmer"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "cj.ka@gma.com"}
    - slot{"emailid": "cj.ka@gma.com"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_7
* restaurant_search{"location": "kota"}
    - slot{"location": "kota"}
    - check_location
    - slot{"location": "kota"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "kota"}
    - utter_ask_email
* dont_send_email
    - utter_goodbye
    - action_restart

## interactive_story_8
* restaurant_search{"location": "jalandhar"}
    - slot{"location": "jalandhar"}
    - check_location
    - slot{"location": "jalandhar"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Mexican"}
    - slot{"cuisine": "Mexican"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "jalandhar"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abi122@hmmaili.co.in"}
    - slot{"emailid": "abi122@hmmaili.co.in"}
    - action_send_email
    - utter_goodbye
    - action_restart
