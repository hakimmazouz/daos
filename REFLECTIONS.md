# Reflections

## The many layers in Nest.js

Nest.js really goes heavy on Dependency Injection and has lots of layers in order to make the app modular, but I feel like it sometimes complicated things maybe too much, especially in combination with typescript.

For example I found that in order to get the current user from the request in the routes of controllers where I am not protecting the route, I still had to use a "Fake" auth guard that just passes the user through.

## React Router V6 is pretty rad

I found React Router v6 to be an absolute joy to use, the loader/action system together with the Form component is genius, and you can even get it up and running with SSR if you wanted to by using Remix as the surface level API is almost the same.

I definitely feel more prepared now should I be put to work on a Nest.js codebase, however I'm still partial to "convention over configuration" MVC frameworks like Rails, Laravel and Phoenix.
