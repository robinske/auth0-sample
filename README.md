# Auth0 Python Web App Sample

This sample demonstrates how to add authentication to a Python web app using Auth0.

# Running the App

To run the sample, make sure you have `python` and `pip` installed.

Add the following to your `~/.bash_profile` or environment file of your choice. For more info on setting environment variables, [check out this post.](https://www.twilio.com/blog/2017/01/how-to-set-environment-variables.html)

You can sign up for an Auth0 account and get these values here: [https://auth0.com/](https://auth0.com/). This project was downloaded and updated from the [Python quickstart.](https://auth0.com/docs/quickstart/webapp/python).

AUTH0_CLIENT_ID='<insert here>'
AUTH0_CLIENT_SECRET='<insert here>'
AUTH0_CALLBACK_URL='http://localhost:3000/callback'
AUTH0_DOMAIN='kelley.auth0.com' #update for your domain
AUTH0_AUDIENCE='<insert here>'

If you are not implementing any API you can use `https://YOUR_DOMAIN.auth0.com/userinfo` as the audience.
Also, add the callback URL to the settings section of your Auth0 client.

Register `http://localhost:3000/callback` as `Allowed Callback URLs` and `http://localhost:3000` 
as `Allowed Logout URLs` in your client settings.

Run `pip install -r requirements.txt` to install the dependencies and run `python server.py`. 
The app will be served at [http://localhost:3000/](http://localhost:3000/).


## License

Forked from [Auth0](https://auth0.com) with <3

This project is licensed under the MIT license. See the [LICENSE](LICENCE) file for more info.
