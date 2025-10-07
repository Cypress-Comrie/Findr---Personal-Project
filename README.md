# Welcome to my Personal project! CodeNamed Findr
## The Big Plan  
I have had this Idea for a while i originally came up with the base of it for a group project which we did implement. we made an activity chooser app using the bored api.
i really liked the idea of the "tinder like" theme swipping right for yes and left for no.

The idea for Findr is a couples based app where you can find movies to watch together instead of spending hours deciding and looking you can open up findr throughout the day swipe a couple of times and have a match by the time you's are ready to watch.

* Im thinking we need to create a relationship through accounts where you both swipe on a list of randomized movies when you swipe (right) yes it adds it to a personalised watchlist 
and if your partner also swipes yes on the same movie it takes it to a combined watchlist.

* I want the user to be able to refine their search down to what theyre looking for so Ill add a catagories selector and a date range selector 
 
* have buttons that take you to a personalised watchlist aswell as to your combined watchlist

View Figma at `https://www.figma.com/design/4xp7nEanhh7RuT1W9hqCfq/Finder-Template?node-id=0-1&t=bXjUQWb82nx8DTgS-1`




## The Road Map
* figure out how to use figma to create a template that im happy to use for the web app
* Create the tinder like system that'll use a movie api to choose random movies 
* Get the api and set it up
* add in a loading state 
* Create the refining tools Catagories/date range 
* add button to take you to watchlist
* figure out how to make accounts work. Possibly with databases?
* add button to take you to shared watchlist 
* CSS it all along the way

This may and most likely will be expanded upon the more I think about or remeber things I need to do! 

#### **Stretch**
* Have a pop up like tinder when a match is made for a more in your face representation 
* A play button that takes you to a website to view the movie (Not sure on the legalities behind this)
* add a why not feature, letting the user have a reason for not wanting to watch a certain film

# Boilerplate: React with Express and Vite

This is a starter project that uses Vite to bundle a React app and Express to serve it in production. Express is used in development to serve an API server.

Vite React App: [http://localhost:5173](http://localhost:5173)
Express API Server: [http://localhost:3000](http://localhost:3000)

Requests to `http://localhost:5173/api` are proxied to `http://localhost:3000/api`.

## Setup

### Installation

#### **From the Github UI**

See the instructions [here](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) to use Github's feature to create a new repo from a template.

```
git clone [your-project-ssh-address]
cd [your-project-name]
npm install # to install dependencies
npm run dev # to start the dev server
```

You can find the client running on [http://localhost:5173](http://localhost:5173).

[Provide feedback on this repo](https://docs.google.com/forms/d/e/1FAIpQLSfw4FGdWkLwMLlUaNQ8FtP2CTJdGDUv6Xoxrh19zIrJSkvT4Q/viewform?usp=pp_url&entry.1958421517=boilerplate-react-api)
