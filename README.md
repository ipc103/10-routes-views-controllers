## CHALLENGE - Build out a route, controller action and view that displays all of the Tweets. Each tweet should link to a tweets show page.

## POST LECTURE CHALLENGES - Build out a route, controller action and view that displays all of the Tweets. Each tweet should link to a tweets show page.


1. I want to use mass assignment in Rails. Meaning, I want to be able to do this in my `create` action in my TweetController.

`tweet = Tweet.create(params[:tweet])`

I can't do this because it's not secure. What security feature in Rails will allow me to do this?

2. My edit and new forms look very similar... I want to be able to use the same form for new and for edit.

  + A different Rails helper to generate the form - form_tag won't work because I can't dynamically set the method and the action
  + A way to render HTML on two different pages
