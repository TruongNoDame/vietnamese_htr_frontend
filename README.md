# Vietnamese Handwritten Text Recognition

## Introduction
Our handwriting recognition project uses the current state-of-the-art scene text recognition model [CLIP4STR](https://github.com/VamosC/CLIP4STR). We use [FastAPI](https://fastapi.tiangolo.com/) to create the API for our application, and use [ReactJS](https://react.dev/) , [Bootstrap v4.6](https://getbootstrap.com/docs/4.6/getting-started/introduction/) and [Konvajs](https://konvajs.org/index.html) to create the interface for our application and call the API. This repo will show you how to run a reactjs app to get an interface for Vietnamese Handwritten Text Recognition.

- Describe the problem of handwriting recognition: with the input being an image containing handwriting that needs to be recognized, the output is the text in the image in the form of digital data.
![htr_in_out](https://github.com/TruongNoDame/vietnamese_htr_frontend/blob/main/images/htr_in_out.png)
## Run Demo
Open cmd and follow these steps: 
- run: `git clone` this repo.
- run: `cd vietnamese_htr_frontend`
- run: `npm install`
- run: `npm start`
- open browser and open link `localhost:3000`
  
## Get API
This application will not be able to run without the return api so I suggest you run [API]() first then run this repo.
