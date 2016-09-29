XixiNannanBlog Deployment at Heroku
====================================


When running `git push heroku master` and need to enter user name and password, run the following command to get a token as password:

    heroku auth:token

Run the following to ensure at least one instance of the app is running

    heroku ps:scale web=1

Then

    heroku open
