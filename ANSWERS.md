# Q0: Why is this error being thrown?

We haven't made our Pokemon model.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

When the button is clicked, a post request is sent to the "capture" path defined in routes.rb. This capture path then routes to the capture method in the PokemonsController, and capture is called with the parameters specified "id: @pokemon". This passes into the capture method a dictionary where the key 'id' maps to the current pokemon (@pokemon).

# Question 3: What would you name your own Pokemon?

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app
