# Redux News Reader
## Project #56 from Codecademy's Full Stack Engineer Career Path
### By Anton Vlasenko (AntonV0)  
## Project Outline
This project is a news reader where users can view and comment on various articles. The goal here is to use the Redux Toolkit's utilities, namely createAsyncThunk and createSlice, to add asynchronous functionality to the comments feature in this Redux application.

I found that the most challenging part was to make all articles display after adding the starter code, before focusing on the project's aim of adding comment functionality. I solved this by installing the Mock Service Worker (MSW) with **npm install msw --save-dev** in the root directory, and then creating a service worker public directory with **npx msw init ./public**. Both changes were saved in package.json, under the msw worker directory path.
## What I Learned
  - Building asynchronous action creators with createAsyncThunk
  - Generating slices with createSlice 
  - Using the Fetch API to fetch comments from the Mock Service Worker (which replicates the functionality of an external API)
  - Adding Extra Reducers to slices using the "builder" notation
  - Dispatching actions for each pending/fulfilled/rejected promise lifecycle states
***
*Please note that in most cases, in each project, the first or second commit is the starter code provided by Codecademy.*
