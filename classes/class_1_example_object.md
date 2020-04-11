### Class: Soda

**Baja Blast:**
- soda_color: "blue"
- soda_recipe: {"cups sugar" ==> 2, "cups carbonation" ==> 2, "cups blueberry flavoring" ==> 1}
- soda_amount: 16
- soda_lid_style: "twist cap"


**Methods:**
 - food_coloring ==> soda_color ==> "Green"; soda_recipe ==> ["drops food_coloring"] = 2
 - add_ingredient ==> soda_recipe ==> ["cups raspberry"] = 1
 - refill==> soda_amount ==> 21 fl oz.
 - change_bottles ==> soda_lid_style ==> "no lid"
