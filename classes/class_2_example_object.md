**Class 2 Example Object**

*Object:*  `yehuda_klug_breakfast_receipt`

*Attribute values:*

```ruby
# num_items_total
3

# total_cost
8.95

# items_ordered
{coffee: 1.45, orange_juice: 2.00, pancakes: 5.50}

# is_paid
false
```

*Results of the method being called:*

```ruby
# add_item(item, price)
yehuda_klug_breakfast_receipt.add_item(:hash_browns, 3.75)
# items_ordered = {coffee: 1.45, orange_juice: 2.00, pancakes: 5.50, hash_browns: 3.75}
# total_cost = 12.70

# remove_item(item)
yehuda_klug_breakfast_receipt.remove_item(:orange_juice, 2.00)
# items_ordered: = {coffee: 1.45, pancakes: 5.50, hash_browns: 3.75}
# total_cost = 10.70

# add_tip(percent)
yehuda_klug_breakfast_receipt.add_tip(15)
# total_cost = 12.31

# pay
yehuda_klug_breakfast_receipt.pay
# is_paid = true
```