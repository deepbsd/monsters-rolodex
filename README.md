# Monsters Rolodex

Fun little app that fetches a list of users from typicode.com, grabs a random image from robohash.org, 
and creates a little rolodex type card with a "monster's" name and email.  

I've worked on larger react apps, but it's been a little while and this looked fun.

I got this from the Udemy course "Complete React Developer in 2019 (w/ Redux, Hooks, GraphQL)".  So
far, I'm pretty impressed with the class.

My only regret at this point is that the gh-pages deploy didn't work.  For some reason, I can't seem to hit 
that page and have it render.  The app runs locally just fine though.  This might have something to do 
with the following:

1. I used npm instead of yarn as the instructor did.  (I had to translate the commands on the CLI and in package.json)
2. I already have a deployment at deepbsd.github.io that might interfere with deepbsd.github.io/monsters-rolodex

As I look at the page with inspector tools, I see a webpack minified script was supposed to create the page, but unfortunately it
didn't.  There were a number of resources that simply aren't available apparently.  The build script failed.  Not sure how or why.
