## Bloccit: a Reddit replica to teach the fundamentals of web development and Rails.

Bloccit is a Ruby on Rails application that allows users to create topics and posts. Users are able to up/down vote posts as well as favorite them. All aspects for this app were custom built, including authentication and authorization, in order to gain a thorough understanding of their functionality.

This app was created as part of the Bloc Full Stack Web Development course.

# Features

-Users can create a standard account in order to create and edit topics and posts.

-Users can up/down vote any post. A list of their posts is displayed on their profile with their vote score.

-Users can favorite posts, which are then saved on their user profile for easy tracking.

# Deployment

To run Bloccit locally:

-Clone the repository

-Run `bundle install`

-Create and migrate the SQLite database with `rake db:create` and `rake db:migrate`

-Start the server using `rails s`

-Run the app on `localhost:3000`
