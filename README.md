# Startup Generator

source https://gist.github.com/epoch/b10e6d223581af5520869bd13e918307#startup-generator
Write a javascript program that randomly generates a startup idea for you. Each time you run it, you should see a random combination for a great startup idea. 

Use the arrays below to get started:

```javascript
let thisArray = ["Skynet","Digital Music Distribution",
"FitBit","Realtime Data","ManPacks","Landing Page",
"Conversion Funnel","Social Network","Airbnb","SnapChat",
"Bang With Friends","HTML5 App","Google Analytics","Mapreduce Query",
"Node.js Server","KickStarter","Match.com","Adultfriendfinder",
"Pinterest","Amber Alert System","Groupon","Appstore","Digital Magazine",
"Distributed Social Network","Quadcopter","Daring Fireball",
"Content Distribution Network","Analytics Platform","OpenTable",
"LinkedIn","Brick and Mortar Solution","Aggregator","Social Game","jQuery Plugin","Game-based Incentive","Foursquare","YouTube","WeedMaps","Texts From Last Night","Ponzi Scheme","1-800-Flowers","Cash4Gold","Online Marketplace","Viral Marketer","Wearable Computer","Google Glass App","Facebook Marketplace","Zivity","Playboy","Cloud Storage Provider","Kindle Fire App","Pandora","Green Tech Program","Eco-Friendly Marketplace",
"Netflix","Amazon","Zappos","Reddit","Enron","Wordpress","iPhone App","Android App","Meme Generator","Crowdsourcing App","Mac App","SEO Optimizer","Apartment Guide","Social CRM","Database Abstraction Layer","Microblogging Service","Product Curation Service","API","New Social Platform","Tumblr","Deal Finder","CPA Ad Network","Collaborative Filter","Shopping Site","Digg 2.0",
"Recommendation Engine","News Recommender","Neural Network","Tesseract OCR engine","Unreadable CAPTCHA","Mobile Ecosystem","Flickr","Salesforce.com","Twitter Filter","Wikipedia","Yelp"];

let thatArray = ["Facebook Platform","Erlang Enthusiasts","Ex-Girlfriends",
"Mitt Romney's Hair","Laundromats","Celebrity Gossip","Endangered Species","Pandas","Middle Schoolers","Alpha Phi Girls","Funeral Homes","Chinese Take-out","Ex-Convicts","Fast Casual Restaurants","Marketers","Qualifying Leads","Funeral Homes","Farmers","Cougars","Pilots","Gynecologists",
"Cracked iPhone Apps","Stolen Goods","Adult Dancers","People Who Hate Groupon","Hunters","Sysadmins","Bath Salts","Nootropics","California","Government Corruption","Political Attack Ads","Whiskey Lovers","Parking Tickets","Highway Accidents","Traveling","Airlines","Presentation Tools","Your Boss","Ponzi Schemes","Your Finances","Restroom Attendants","Your Aquarium","Your Cat's Litter Box","Pets","Alcoholics",
"Camp Counselors","Nature Blogs","World of Warcraft","Models","Family Guy Enthusiasts","The Army","Cheap Vodka","Tech Incubators","Star Trek Conventions","Presentation Tools","Small Businesses","Beer","Nightclub Lines","Semi-Active Volcanoes", "Sanctimonial Artifacts","Traveling Abroad","Your Mom","Billionaires","Happy Hours","Ugg Boots","The Homeless","Blacking Out","Red Wine","Happy Families","Social Outcasts",
"Surgeons","Pounding Jagger Bombs","Textbooks","Coffee Shops","Baristas"];
```

Hint: use the built in function `Math.random()` to generate a random number between 0 and 1.


## example usage on the terminal:

```
% node startup_generator.js
Fitbit for Funeral Homes
```

allow the user to pass in an optional name when they run the program to get a personalised message.
```
% node startup_generator.js dt
hey dt, here's an idea for ya!
Adultfriendfinder for Marketers
```

