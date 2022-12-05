# Califica Tu profe

A full-stack web app where students can leave public but anonymous reviews of their professors, in Spanish.

**Link to project:** https://calificatuprofe.herokuapp.com/

![Califica Tu Profe app landing page](https://raw.githubusercontent.com/diathekez/calificatuprofe/master/public/imgs/calificatuprofe-app.png)

## How It's Made

**Tech used:** HTML, CSS, JavaScript, EJS, Express, Node.js, MongoDB, Tailwind (with DaisyUI)

**Important:** You must have [Node.js](https://nodejs.org/en/download/) installed and both a [MongoDB](https://www.mongodb.com/) and a [Cloudinary](https://cloudinary.com/) account. Both [Tailwind](https://tailwindcss.com/docs/installation) and [DaisyUI](https://daisyui.com/docs/install/) have already been configured in the app, but I recommend checking out the documentation if you're new to using CSS frameworks.

I wanted this to be a basic, fast-loading app. So I used EJS rather than React because I didn't want to keep track of useState. The second thing to decide was the styling. Tailwind is a very popular option, so I went with DaisyUI because of the basic and elegant components it offers. For the back-end, nothing fancy, just Node and MongoDB.

## Optimizations

I originally thought about building this app with React but at the time I wasn't too confident using it. Ironically, I realize now that using React would have prevented some headaches I had and made the code much cleaner, reusable, and efficient. When I have time in the future, I'll rebuild the app with React.

## Lessons Learned

It sounds funny but I learned a lot about CSS making this app. I've used Materialize and Boostrap before, as well as Tailwind, but it's been while building this app that I understood the limitations of some frameworks. Using pre-built components is faster, obviously, but not having much choice in customization can be a little frustrating in how you have to finnagle around with custom CSS.

## Examples:

Take a look at these couple examples that I have in my own portfolio:

**Precrastinator:** https://github.com/diathekez/precrastinator

**For Blossom:** https://github.com/diathekez/for-blossom-api

**To-do List:** https://github.com/diathekez/todo-list-app

# Install

`npm install`

# Things to add

- Create a `.env` file in config folder and add the following as `key = value`
  - PORT = 3000
  - DB_STRING = `your database URI`
  - CLOUD_NAME = `your cloudinary cloud name`
  - API_KEY = `your cloudinary api key`
  - API_SECRET = `your cloudinary api secret`

# Run

`npm start`
