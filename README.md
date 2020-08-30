
# EasyCook

## FullStack Web Development Milestone Project-4

## Description

kkkkkkkk

# UX

### Target Audience

 kkkkk

 ### User Stories

 1. As a user, I want to 
 2. As a user, I want to 
 3. AS a user, I want to 
 4. As a user, I want to 
 5. As a user, I want to 
 6. As a user, I want to 

 ### Site Owner Stories

 1. As a owner, I want to 
 2. As a owner, I want to 
 3. As a owner, I want to 
 4. As a owner, I want to 
 5. As a owner, I want to 
 6. As a owner, I want to 

 ## Design

 The website design is .The design inspiration is taken from the **Code Institute's Fullstack web Development Project**.

## Wireframes

I used [AdobeXD](https://creativecloud.adobe.com/apps/download/xd?promoid=B8NR3RT1&mv=other) to create wireframes which will provide an overview of how the website will look.

## Database

db.sqlite3 and Amazone Web Services are used to store data at the backend.

## Features
### Existing Features
- **Logo** - 
- **products** - 
            - **Sorting Products** -
            - **Back to Top Button** -
- **Special Offers** - 
- **Shopping Bag** - 
            - **Remove / Update** -
            - **Secure Checkout** -
                        - **checkout page** -
            - **Keep Shopping** -
- **My Account** - 
            - **Registration** -
            - **Login** -
            - **logout** -
            - **Manage Products** -
- **Search** - 
- **Purchase Button** - 

### Features Left to Implement

- **Sorting products by rating**
- **Free Delivery Offers**
- **Size selection for Clothes**

## Technologies Used

- **HTML5**
- **CSS3**
- **JQuery**
- **Django**
- **[Stripe](https://stripe.com/en-se)**
- **[Bootstrap Framework](https://getbootstrap.com/)**
- **[Python](https://www.python.org/)**
- **[Amazon Web Services](https://aws.amazon.com/)**
- **[Django-allauth](https://django-allauth.readthedocs.io/en/latest/installation.html)**
- **[AdobeXD](https://creativecloud.adobe.com/apps/download/xd?promoid=B8NR3RT1&mv=other)**
- **[Google Fonts](https://fonts.google.com/)**
- **[Git & Github](https://github.com/)**
- **[Heroku](https://www.heroku.com/#)**


## Testing

Google developers tool has been used to test the project constantly form the  beginning to identify any error or to see how the changes looks like on different screen sizes.

### Responsiveness on different browsers & Mobiles

The website looks fine and work properly on following web browsers and mobiles when tested on them.
- Google Chrome
- Microsoft Edge
- Firefox
- Opera
- All devices listed in responsive section of the DevTools on the google chrome. From "Moto G4" to "iPad Pro".

### Code Validation

The code has been validated by using;

- [W3C Markup Validation Service for CSS](https://jigsaw.w3.org/css-validator/)
- **flake8**

## Deployment to Heroku

- **[fitness365 Live Page](https://fitness365.herokuapp.com/)**

- **[Fitness365 Repository](https://github.com/IIxShahinxII/Fitness365)**

1. Login to **[Heroko](https://www.heroku.com/)** account.
2. Click on **New** at the right top corner and click on **Create new app**.
3. Choose **App name** and a **region**. Then click on **Create app**.
4. Go to terminal window and create **requirements.txt** by running command **pip3 freeze --local > requirements.txt**
5. Then create **Procfile** by running command **echo web: python app.py > Procfile** **Remember P is capital**
6. Add these files to stagging area by running command **git add requirements.txt** & **git add Procfile**.
7. Then commit these file respectively by running command **git commit -m "Added requirements.txt** & **git commit -m "Added Procfile**.
8. Then push these files to **github** by running command **git push**
9. Go back to **Heroku** to your **App** and click on **Deploy** tab.
10. Then go to **Deployment Method** and click on **Github Connect to Github**.
11. Then make sure your **Github Profile** is displayed and add your **repository name** and click on **Search**.
12. Once it find your repository then click on **Connect**.
13. Now go to **Settings** at the top. Then click on **Reveal Config Vars**.
14. In **Config Vars** add **IP** with value **0.0.0.0** then add **PORT** as **5000** then add **SECRET_KEY** then add **MONGO_URI** and then add **MONGO_DBNAME** which is the name of database.
15. Now go back to **Deploy** tab and click on **Enable Automatic Deploys**.
16. Now click on **Deploy Branch**
17. It will take a minute and display a message that **Your app was successfully deployed**.
18. Click on **View** to launch your deployed app.

## Local Deployment

1. Go to [Fitness365 Repository](https://github.com/IIxShahinxII/Fitness365)
2. Click on **Code** beside **Gitpod**.
3. A drop down menu open then click on **Download Zip**
4. Unzip the downloaded zip file.
5. Open app.py file and install requirements.txt by running command **pip3 install -r requirements.txt**.
7. Create env.py file and add **SECRET_KEY**.
8. Now run the app.py by running code **python3 manage.py runserver**.

## Credits
### Media

- All the images of products page are taken from google image's section **Google**.
- The background image of home page has been taken from **Google**

### Acknowledgements
- Code Institute's **Fullstack Web Development's Project** I follow it to design and develop my **Fitness365** website.
- The project is based on **Bootstrap**, **Django-allauth** and **Stripe**, so the codes are taken from : 
            [Bootstrap Framework](https://getbootstrap.com/), 
            [Django-allauth](https://django-allauth.readthedocs.io/en/latest/installation.html),
            [Stripe](https://stripe.com/en-se)
- A special thanks to my mentor **Maranatha** for his valuable feedback during mentoring sessions.

## Disclaimer
This project is for educational purposes only.

