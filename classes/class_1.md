**Class 1 Example**

One class that might exist in a restaurant would be the `Menu_Item` class.  The `Menu_Item` class could have instances like `breakfast_sandwich`, `spinach_salad`, and `black_bean_burger`.  

Some example attributes of the `Menu_Item` class are:

* `item_type` (string)
* `item_price` (float)
* `ingredient_list` (array)
* `is_gluten_free` (boolean)
* `is_available` (boolean)

Some example methods of the `Menu_Item` class are:

* `change_price` (updates the price of the `item_price` attribute)
* `change_ingredient` (changes one or more ingredients in the `ingredient_list` attribute; this can also change the value of `is_gluten_free`)
* `change_type` (changes the string associated with the type of product that the item is.  For example, `black_bean_burger` may be categorized as `vegetarian`, but maybe we want to move it to `vegan`.)
* `change_available_time` (changes what time the item is available.  For example, the `black_bean_burger` is available from 11:00am to 3:00pm, and now we want to change it to be available from 11:00am to 5:00pm.)