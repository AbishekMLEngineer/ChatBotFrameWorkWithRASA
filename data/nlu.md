## intent:affirm
- yes
- yep
- yeah
- indeed
- that's right
- ok
- great
- right, thank you
- correct
- great choice
- sounds really good
- thanks
- sure thing
- fine with me
- yup

## intent:goodbye
- bye
- goodbye
- good bye
- stop
- end
- farewell
- Bye bye
- have a good one

## intent:send_mail
- sure my emailId is [silcis.as12@gmail.com](emailid)
- ok [abc.fhug@gmail.com](emailid)
- [abchvcsh.fhug@xgmail.com](emailid)
- [abbsdhbs808csh.fhug@xgl.co.in](emailid)
- [abbs808.1213@xgl.co.in](emailid)

## intent:greet
- hey
- howdy
- hey there
- hello
- hi
- good morning
- good evening
- dear sir

## intent:deny
- No
- No thanks
- not Required
- No thanks I am good
- Nope


## intent:restaurant_search
- i'm looking for a place to eat
- I want to grab lunch
- I am searching for a dinner spot
- I am looking for some restaurants in [Delhi](location).
- I am looking for some restaurants in [Bangalore](location)
- show me [chinese](cuisine) restaurants
- show me [chines]{"entity": "cuisine", "value": "chinese"} restaurants in the [New Delhi]{"entity": "location", "value": "Delhi"}
- show me a [mexican](cuisine) place in the [centre](location)
- i am looking for an [indian](cuisine) spot called olaolaolaolaolaola
- search for restaurants
- anywhere in the [west](location)
- I am looking for [asian fusion](cuisine) food
- I am looking a restaurant in [294328](location)
- in [Gurgaon](location)
- [South Indian](cuisine)
- [North Indian](cuisine)
- [Italian](cuisine)
- [Chinese]{"entity": "cuisine", "value": "chinese"}
- [chinese](cuisine)
- [Lithuania](location)
- Oh, sorry, in [Italy](location)
- in [delhi](location)
- I am looking for some restaurants in [Mumbai](location)
- I am looking for [mexican indian fusion](cuisine)
- can you book a table in [rome](location) in a [moderate]{"entity": "price", "value": "mid"} price range with [british](cuisine) food for [four]{"entity": "people", "value": "4"} people
- [central](location) [indian](cuisine) restaurant
- please help me to find restaurants in [pune](location)
- Please find me a restaurantin [bangalore](location)
- [mumbai](location)
- show me restaurants
- please find me [chinese](cuisine) restaurant in [delhi](location)
- can you find me a [chinese](cuisine) restaurant
- [delhi](location)
- please find me a restaurant in [ahmedabad](location)
- please show me a few [italian](cuisine) restaurants in [bangalore](location)
- test
- can you find me a [Mexican](cuisine) restaurant in [andaman](location)?
- [Rs 300 to 700](price)
- [More than 700](price)
- [Lesser than 300](price)
- [900](price)
- [600](price)



## synonym:4
- four

## synonym:Delhi
- New Delhi

## synonym:bangalore
- Bengaluru
- Bengalur
- banglor

## synonym:Delhi
- New Delhi
- Dilli
- Nai Dilli
- Deli

## synonym:Mumbai
- bambai
- bombay

## synonym:Chandigarh
- chandighar
- chandigarg




## synonym:chinese
- chines
- Chinese
- Chines






## synonym:mid
- moderate

## synonym:vegetarian
- veggie
- vegg

## regex:greet
- hey[^\s]*

## regex:pincode
- [0-9]{6}
