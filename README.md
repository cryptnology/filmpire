# Filmpire

An AI powered movie app that allows you to search for the latest movies via categories, genres or a search bar and is fully responsive with the choice of using a dark or light theme. You can also create / log in to your profile where can see all your favourite and watchlisted movies. The app is built using React, Redux, React Router, Alan AI, Axios and the TMDB api.

<img width="1717" alt="filmpire" src="https://user-images.githubusercontent.com/85605968/233777017-aed32ff5-2824-4bce-a30f-e41cb2611f1b.png">

## Installation

After cloning or downloading the repo run `yarn` or `npm install` to install the dependencies. Make a `.env` using the `.env.example` where you will need to fill in `REACT_APP_TMDB_KEY` and `REACT_APP_ALAN_KEY`. To get these keys you will need to sign up (Don't worry these services are free for development purposes) on [TMDB](https://www.themoviedb.org) and then get your api key [REACT_APP_TMDB_KEY](https://www.themoviedb.org/settings/api) in your settings. Do the same for [Alan AI](https://alan.app). After signing up create a new empty project, click the Integrations button at the top to get your `REACT_APP_ALAN_KEY`. If you don't want to use Alan AI just comment out `useAlan();` on line 14 in `App.jsx`.

## Usage

Please visit the [Filmpire](https://filmpire-omega.vercel.app) website and search for your favourite movies to your heart desire. When using the AI here are the commands you can use.

```
'What does this app do?',
'What can I do here?',
'What is this app about?',
'Make it dark',
'Make it light',
'Log in',
'Log out',
'Go to {Genre name}',
'Search for {Query}',
'It's Halloween.',
'I want to get scared',
'Give me something funny.',
'I want to laugh',
'Surprise me'
```
