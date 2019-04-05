# github-drone-netlify
This project is an example of how to deploy a web site from drone.io using Netlify.

## Authentication
To use the deploy command you need to authenticate drone against
netlify. This is done by setting the NETLIFY_AUTH_TOKEN environment
variable. This value should be stored as a drone secret.

To create the access token in Netlify go to Applications > Personal
Access Tokens which can be found [here](https://app.netlify.com/user/applications).

## Deployment Target
To tell Drone which Netlify site you want to deploy to you have to set
the NETLIFY_SITE_ID environment variable. The site id is printed when
you run the netlify init command.

## Location
This site is available at the following [url](https://drone-netlify.netlify.com/).
