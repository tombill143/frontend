# Fullstack frontend

This repo iis being supplied in visual studio code but made in notepad++

The frontend is running here: https://flawless-branch.surge.sh
The backend is running here: https://cine-mama.herokuapp.com/

The code for the backend api can be found here: https://github.com/behu-kea/tomas-order-site

## Running the project

First make sure that [the project shown above](https://github.com/behu-kea/tomas-order-site) is running locally

Now make sure that whereever you will be running your frontend app is added to `allowedOrigins` in `src/main/java/swc3/demowebshop/config/WebConfig.java`. This will give the frontend access to the rest api.

In the `settings.js`

- Update the variable `localApiUrl` to be the url for where the project mentioned above is running locally
- Update the variable `prodApiUrl` to be the url for where the project mentioned above is running in production

To run the project locally click the `Go live` button in the bottom right corner. This will open the project with Liver Server. The url should be http://127.0.0.1:5500/ (depending on the port)

Alternatively, to run the project in notepad++, click run, Google Chrome and you will see the frontend. 

## Deploying

To deploy this projet use https://surge.sh/. There is a super nice video that shows how this is done!
