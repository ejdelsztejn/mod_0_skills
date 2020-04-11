**Class 2 Example**

One class that might exist in a restaurant would be the `Receipt` class.  Some instances of the `Receipt` class could be `jessica_edelstein_lunch_receipt`, `matilda_jones_dinner_receipt`, and `yehuda_klug_breakfast_receipt`.

Some example attributes of the `Receipt` class are:

* `num_items_total` (integer)
* `total_cost` (float)
* `items_ordered` (hash: *item => price*)
* `is_paid` (boolean)



Some example methods of the `Receipt` class are:

* `add_item(item, price)` (adds item name and price to `items_ordered`. Updates `total_cost`.)
* `remove_item(item)` (removes item from `items_ordered`.  Updates `total_cost`.)
* `pay` (changes boolean value of `is_paid` to `true`.)
* `add_tip` (adds additional tip money.  Updates `total_cost`.)