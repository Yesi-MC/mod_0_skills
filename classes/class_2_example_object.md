instance: pancakes

attributes
name: "Pancakes"
ingredients: ["flour", "sugar", "milk"]
is_ready: false
temperature: "warm"


methods
pancakes.name_change("Famous Stack") (this will change the name from "Pancakes"
  to "Famous Stack")
pancakes.add_ingredients("blueberries") (this will add "blueberries" to our  
  ingredients array)
pancakes.cook (this will change `is_ready` from false to true)
pancakes.check_temperature (this will return "warm")
