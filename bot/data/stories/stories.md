## Generated Story 3368280294361445118
* greet
    - utter_greet
    - utter_greet1
    - utter_greet2
* locale{"locale": "brasilia"}
    - slot{"locale": "brasilia"}
    - action_weather
* temperature{"locale": "manaus"}
    - slot{"locale": "manaus"}
    - action_temperature
* wind{"locale": "aguas claras"}
    - slot{"locale": "aguas claras"}
    - action_wind
* sunrise_sunset{"locale": "salinas"}
    - slot{"locale": "salinas"}
    - action_sunrise_sunset
* humidity{"locale": "paris"}
    - slot{"locale": "paris"}
    - action_humidity
* goodbye
    - utter_goodbye

## Generated Story 6172655584602252502
* greet
    - utter_greet
    - utter_greet1
    - utter_greet2
* temperature{"type": "temperatura", "locale": "brasilia"}
    - slot{"locale": "brasilia"}
    - slot{"type": "temperatura"}
    - action_local
    - slot{"type": null}
* choose{"choice": "2"}
    - slot{"choice": "2"}
    - action_temperature
* inform{"locale": "goiania"}
    - slot{"locale": "goiania"}
    - action_local
    - slot{"type": null}
* choose{"choice": "1"}
    - slot{"choice": "1"}
    - action_weather

