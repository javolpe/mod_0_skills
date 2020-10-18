Dark Horse Merlot, California 2013 750ML

Attributes:

`type_of_wine` (Merlot)

`abv` (13.5)

`price` (hash) {glass: 5, bottle: 22,}

`in_stock` (true)

Methods:
`give_description` ('#{wine_name(would print 'Dark Horse')} is a #{type_of_wine (print 'Merlot')} from #{location_origin (print 'California')}.')

`give_serving_suggestion_oz` (5)

`calculate_cost` (22)

`check_availability` (yes) - (would set `in_stock` to true based on data in hash `wine_inventory`.  Hash would like like `wine_inventory = {"dark_horse_merlot" => 5, "random_other_wine => 7", etc}`. I'm still new at hashes so not sure the proper syntax for "dark_horse_merlot" but believe it should be in qoutes so the hash knows it is a string and not a variable.)
