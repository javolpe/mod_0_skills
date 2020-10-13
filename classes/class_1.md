## WineList

Attributes:
type_of_wine (string)
abv (float)
price (hash) {glass: x, bottle: y,}
in_stock (boolean)

Methods:
give_description (use string interpolation, tells customer location_origin, type_of_wine, background_facts)
give_serving_suggestion_oz (describes how many ounces poured into 1 glass based on abv)
calculate_cost (gives final cost based on how many glasses and/or bottles ordered)
check_availability (tells waiter if available based on in_stock returning true or false)
