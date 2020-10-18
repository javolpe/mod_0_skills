## Cobb Salad

Attributes:

`vegetarian`: (false)

`dressing`: ("caesar", "ranch", "french",)

`size`: (small)

`price`: (7.99)

`dressings_available`: ["caesar", "ranch", "french","italian"]

Methods:

`add_menu_emoji`: (no action)(checked vegetarian==false so vegetarian_emoji *not* added to menu)

`select_dressing`: ("ranch" - based on dressing selected from `dresings_available`)

`choose_bowl`: ("small white bowl" - instructions given to kitchen based on size == small)

`totaled_cost`: ("32.49" - price gets summed with other items into totaled_cost before tax_applied is calculated)
