# project-todo-api
This is a RESTful API intended for users to list their todos. They can also add items for each movie.

This project was made following the tutorial: https://scotch.io/tutorials/build-a-restful-json-api-with-rails-5-part-one
Author: Austin Kabiru

Todos description includes title and created_by.
Items description includes name and done.

- Ruby version 2.5.1
- Rails version 5.2.2
- Run migrations: $rails db:migrate
- Run the test suite: $bundle exec rspec
- Deploy the rails server: $rails s

# Create a todo using httpie
http POST :3000/todos title=Mozart created_by=1

# Update a todo using httpie
http PUT :3000/todos/1 title=Beethoven

# Delete a todo using httpie
http DELETE :3000/todos/1
