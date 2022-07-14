# ToDo-List-Website
https://tranquil-citadel-69579.herokuapp.com/

Built a dynamic data response To-Do-List website implemented by EJS and connected to backend database MongoDB to operate get, post, delete request from front-end https://tranquil-citadel-69579.herokuapp.com/ by using Node.js, Express.

The most challenging part to build this project was the typo in package.json, I spend lots of time to figure out why my project could not connect with heroku. And the terminal can not let me to git push heroko master and said there is some issue in my json file.
The issue is simple to solve, but it took me a while to found out where the issue was.

After I modified my json file(key map value and do not have comma in last document), and git add* git commit -m "update" git push heroku master, and the website builds successfully by the heroku app.
What I found interested of built a full stack website by myself is that when the webiste is sucessfully released, all the time working on the project is worth it.

Note that this project need to be pushed twice, onece for heroku app and once to update this repository.
So git push -u origin main and then git push heroku, then website be updated at the heroku url.


One more problem to solve is the position of add symbol, the add symbol work nice at the desktop screen and mobile screen that checked by L12.
But in the real phone, the add symbol layout changed, I try to use picture and boostrap, not working, still need the solution.
