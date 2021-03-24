// API calls with d3:
//
// So we actually do need to use flask to deploy the html, because browsers don't let you bring in data from a foreign source. This means that the data must come from the same place as the html itself (ie, the heroku server). This isn't a prolem. All you guys have to do is make sure all your html files are in the "templates" directory, and that all your javascript is in the "static/js" directory. Then, when you put your scripts into your html, the format will be like this: <script src=/static/js/SCRIPT_NAME></script>. Similarly, when you call the API routes, you will not specify a url, but only a path. 
//
// For example, if I go to https://nfl-flask.herokuapp.com/id/
d3.json('/year/2016/three_cone&forty_yard').then(data => console.log(data))
