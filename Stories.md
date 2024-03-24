## User Registration
* greet
  - utter_greet
* inform_wholesaler
  - action_register_wholesaler
* goodbye
  - utter_goodbye

* greet
  - utter_greet
* inform_retailer
  - action_register_retailer
* goodbye
  - utter_goodbye

## Updating User Data
* greet
  - utter_greet
* update_data
  - action_ask_update_preference
* provide_update_preference
  - action_update_user_data
* goodbye
  - utter_goodbye

## Purchasing from Shop
* greet
  - utter_greet
* buy_product
  - action_ask_product_category
* provide_product_category
  - action_ask_product_subcategory
* provide_product_subcategory
  - action_show_available_products
* select_product
  - action_process_purchase
* goodbye
  - utter_goodbye
