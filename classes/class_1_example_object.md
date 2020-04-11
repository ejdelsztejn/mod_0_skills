**Class 1 Example Object**

*Object:* `black_bean_burger`

*Attribute values:*

```ruby
# item_type:
"vegetarian"

# item_price:
8.75

# ingredient_list:
["black beans", "flour", "olive oil", "yellow onion", "garlic", "cumin", "chili powder", "bread crumbs", "Worcestershire sauce"]

# is_gluten_free`:
false

# is_available
true # assuming that the current time is 1:00pm
```

*Results of the method being called:*

```ruby
# change_price(price)
black_bean_burger.change_price(9.75)
#	=> 9.75

# remove_ingredient(ingredient)
black_bean_burger.remove_ingredient("bread crumbs")
# => ["black beans", "flour", "olive oil", "yellow onion", "garlic", "cumin", "chili powder", "Worcestershire sauce"]

# change_type(type)
black_bean_burger.change_type("vegan")
# =>"vegan"

# change_available_time(start_time, end_time)
black_bean_burger.change_available_time(11:00, 5:00)
# => true
```

