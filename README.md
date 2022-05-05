# The Django Hub 2.0 (server side code)

This is the server side code for [The Django Hub 2.0](https://thedjangohub.netlify.app/).

## Some information about the project

The Django Hub 2.0 is the new version of [The Django Hub](https://github.com/jbbadano/the_django_hub), a blog project I made a few months ago using Django and PythonAnywhere for
deployment. This time I used the **Django Rest Framework** for building an **RESTful API** connecting the server side code 
to the **React** [client side code](https://github.com/jbbadano/the_django_hub_2.0_client). I deployed the backend with *Heroku*, and the frontend with *Netlify*. I used CORS 
(Cross Origin Resource Sharing) headers and axios to succesfully 
connect the backend API with the React frontend, which consumes the API responses. For the database, I used the **Postgres SQL** data store provided by Heroku, which I find a
lot more scalable than the SQLite database I used for the original The Django Hub project. I am happy for having had success in this more ambitious and modern approach of 
structuring the project architecture and deployment. I hope that you enjoy visiting [The Django Hub 2.0](https://thedjangohub.netlify.app/)!

## Next steps

Although I'm happy with how I modernized The Django Hub, the project is still incomplete. The next steps I am working on are establishing some form of user authentication (specifically I'm working with JWT) and letting users of the blog access individual posts.
