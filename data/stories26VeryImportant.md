
## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Chandigarh"}
    - slot{"location": "Chandigarh"}
    - check_location
    - slot{"location": "Chandigarh"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - verify_budget
    - slot{"budgetmin": 300}
    - slot{"budgetmax": 700}
    - slot{"budget_ok": true}
    - action_search_restaurants
    - slot{"location": "Chandigarh"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "cj.kach@gmail.com"}
    - slot{"emailid": "cj.kach@gmail.com"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_2
* restaurant_search{"location": "janxcity"}
    - slot{"location": "janxcity"}
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
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "700", "budgetmax": "10000"}
    - slot{"budgetmax": "10000"}
    - slot{"budgetmin": "700"}
    - action_search_restaurants
    - slot{"location": "Amritsar"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "silcon.12qa@gmal.com"}
    - slot{"emailid": "silcon.12qa@gmal.com"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_3
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "nagpur"}
    - slot{"location": "nagpur"}
    - check_location
    - slot{"location": "nagpur"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "700", "budgetmax": "10000"}
    - slot{"budgetmax": "10000"}
    - slot{"budgetmin": "700"}
    - action_search_restaurants
    - slot{"location": "nagpur"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abc1212.wasdf@ajax.co.in"}
    - slot{"emailid": "abc1212.wasdf@ajax.co.in"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_4
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - check_location
    - slot{"location": "bangalore"}
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
    - slot{"location": "bangalore"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abc.def@gma.com"}
    - slot{"emailid": "abc.def@gma.com"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_5
* restaurant_search{"location": "jammxcddcds"}
    - slot{"location": "jammxcddcds"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - utter_restart
* restaurant_search{"location": "jambuacda"}
    - slot{"location": "jambuacda"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - action_restart

## interactive_story_6
* restaurant_search{"location": "jambarnad"}
    - slot{"location": "jambarnad"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - utter_restart
* restaurant_search{"location": "jamburnagar"}
    - slot{"location": "jamburnagar"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - action_restart

## interactive_story_7
* restaurant_search{"location": "ambujacement"}
    - slot{"location": "ambujacement"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - utter_restart
* restaurant_search{"location": "jamburga"}
    - slot{"location": "jamburga"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - action_restart

## interactive_story_8
* restaurant_search{"location": "jambchbsdcnw"}
    - slot{"location": "jambchbsdcnw"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - utter_restart
* restaurant_search{"location": "fvhvgvv"}
    - slot{"location": "fvhvgvv"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - action_restart

## interactive_story_9
* restaurant_search{"location": "jammu"}
    - slot{"location": "jammu"}
    - check_location
    - slot{"location": "jammu"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "jammu"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abi.def@bahcbh.com"}
    - slot{"emailid": "abi.def@bahcbh.com"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_10
* restaurant_search{"location": "jalandhar"}
    - slot{"location": "jalandhar"}
    - check_location
    - slot{"location": "jalandhar"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - verify_budget
    - slot{"budgetmin": 300}
    - slot{"budgetmax": 700}
    - slot{"budget_ok": true}
    - action_search_restaurants
    - slot{"location": "jalandhar"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abic.sh@gna.co.in"}
    - slot{"emailid": "abic.sh@gna.co.in"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_11
* restaurant_search{"location": "ambarnagar"}
    - slot{"location": "ambarnagar"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - utter_restart
* restaurant_search{"location": "divayghar"}
    - slot{"location": "divayghar"}
    - check_location
    - slot{"location": null}
    - slot{"location_ok": false}
    - action_restart

## interactive_story_12
* restaurant_search{"location": "chennai"}
    - slot{"location": "chennai"}
    - check_location
    - slot{"location": "chennai"}
    - slot{"location_ok": true}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Italian"}
    - slot{"cuisine": "Italian"}
    - utter_ask_budget
* restaurant_search{"budgetmin": "300", "budgetmax": "700"}
    - slot{"budgetmax": "700"}
    - slot{"budgetmin": "300"}
    - action_search_restaurants
    - slot{"location": "chennai"}
    - utter_ask_email
* send_mail
    - utter_ask_emailid
* send_mail{"emailid": "abi.121@gmail.cped.in"}
    - slot{"emailid": "abi.121@gmail.cped.in"}
    - action_send_email
    - utter_goodbye
    - action_restart

## interactive_story_13
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
    - action_search_restaurants
    - slot{"location": "Jammu"}
    - utter_ask_email
* dont_send_email
    - utter_goodbye
    - action_restart
