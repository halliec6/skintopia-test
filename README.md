# Skintopia: Your Personalized Skincare Recommender

## About the Project:
Deciding what skincare product to purchase is extremely complicated. Customers are met with thousands of reviews and products in addition to paid content. Skintopia was created with the goal of simplifying skincare recommendations. Our machine learning model utilizes customer traits such as skin tone, skin type, and product history to generate customized product recommendations. The model was trained on Sephora product and review data.

## Website Link
[Skintopia](https://halliec6.github.io/skintopia/)
## Getting started
1. Clone the repository
2. Install requirements `pip install -r requirements.txt`
### Frontend Setup
Run all commands from the `frontend/`  directory

Project Setup 
```
npm install
```

Compiles and hot-reloads for development
```
npm run serve
```

Compiles and minifies for production
```
npm run build
```

Lints and fixes files
```
npm run lint
```

Customize configuration:  
See [Configuration Reference](https://cli.vuejs.org/config/).

### Backend Setup

#### Run API with Uvicorn
Navigate to the `backend/src/api` folder and run
```
uvicorn recommender_lightfm_api:app --reload
```
#### Troubleshooting
If you are getting a 404 error, make sure the allow_origins host is the correct number as the frontend local host number.

## Acknowledgements
- Thank you to Lucas Pierce for advising our project throughout the year
- Built with [Vue.js](https://vuejs.org/) and [LightFM](https://making.lyst.com/lightfm/docs/home.html) 


## Authors
This project was created and developed by Felicia Patel and Hallie Christopherson as their senior project at California Polytechnic State University, San Luis Obispo. 