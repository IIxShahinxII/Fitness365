
# EasyCook

## FullStack Web Development Milestone Project-4

## Description

This web site is an online store of products that are being used in gym and for  training. It offers different producs and special offers to its user and all people around the world.
People can navigate through the products, select as many as they want and even remove or adjust them before the purchase them.
At the end, they are able to purchase the products that have chosen by providing billing address and entering their card information in the payment form.

# UX

### Target Audience

 Our targets for this project are Users and Site owner. Users and site owner are able to have account and access to to our product to purchase. However, owner of the site is
 the only one who can monitor all the purchases and products,also Add, Edit and Remove products from the website.

 ### User Stories

 1. As a user, I want to be able to get back to the home page.
 2. As a user, I want to be able to have option to select a specific category or to see all product at one page.
 3. AS a user, I want to be able to sort the product by name and price.
 4. As a user, I want to be able to get back to the top page by one click instead of scrolling all the way up.
 5. As a user, I want to be able to see if there is any offers and also select any specific offers if exist.
 6. As a user, I want to be able to see all the products that I have chosen already and also be able to remove or adjust them before I purchase them.
 7. As a user, I want to be able to purchase my selected product/products with my payment card and receiving it/them at my address.
 8. As a user, I want to be able to add more items to my shopping bag without losing them by getting back to product page.
 9. As a user, I want to be able to create an account, login and logout easily and also would be able to see my purchase history and track my on-going purchases.
 10. As a user, I want to be able to find any products that I am looking for by searching them, instead of going through all the products.
 11. As a user, I want to be able to get to the product page by clicking a button, instead of going from the nav links.

 ### Site Owner Stories

 1. As a owner, I want to be able to get back to the home page.
 2. As a owner, I want to be able to have option to select a specific category or to see all product at one page.
 3. AS a owner, I want to be able to sort the product by name and price.
 4. As a owner, I want to be able to get back to the top page by one click instead of scrolling all the way up.
 5. As a owner, I want to be able to see if there is any offers and also select any specific offers if exist.
 6. As a owner, I want to be able to see all the products that I have chosen already and also be able to remove or adjust them before I purchase them.
 7. As a owner, I want to be able to purchase my selected product/products with my payment card and receiving it/them at my address.
 8. As a owner, I want to be able to add more items to my shopping bag without losing them by getting back to product page.
 9. As a owner, I want to be able to create an account, login and logout easily and also would be able to see my purchase history and track my on-going purchases.
 10. As a owner, I want to be able to find any products that I am looking for by searching them, instead of going through all the products.
 11. As a owner, I want to be able to get to the product page by clicking a button, instead of going from the nav links.
 12. As a owner, I want to be able to Add product and Edit product in my site and also Remove product from product page.
 13. As a owner, I want to be able to have access to all the purchases history of the site and monitor them.

 ## Design

 The website design is .The design inspiration is taken from the **Code Institute's Fullstack web Development Project**.

## Wireframes

I used [AdobeXD](https://creativecloud.adobe.com/apps/download/xd?promoid=B8NR3RT1&mv=other) to create wireframes which will provide an overview of how the website will look.

## Database

Postgres from Heroku and Amazone Web Services are used to store data at the backend.

## Features
### Existing Features
- **Logo** - By clicking on logo, user will redirect to home page (main pag).
- **products** - By clicking on products, user would have options to choose different category of products or select All products.
- **Sorting Products** - In product page, user can sort by name from A-Z or Z-A and by price from high-low or viseversa.
- **Back to Top Button** - In product page, use can see a small green button with an arrow pointed top, if he/she click on it will get back to the top.
- **Special Offers** - By clicking on special offers, user would have option to choose different category of offers or select All offers
- **Shopping Bag** - This page will show the products that are selected by user. User will see the total amount and has access to final step which is check out.
- **Remove / Update** - In shopping bg page, user is able to remove item/items and also adjust the quantity.
- **Secure Checkout** - By pressing on this button in shopping bag page, user will be redirected to check out page to compelete the purchase.
- **checkout page** - In this page user must provide billing address and also enter the payment card info to complete the purchase.
- **Keep Shopping** - By clicking on this button, user will be redirected to Product page and can add more items to shopping bag.
- **My Account** - By clicking on my account, user can **Register** if he has not created any account yet. User can **Login** if he/she has created an account already.
User can **logout** if he/she is already logged in. Only site owner has access to **Manage Products** after he login.(site owner need to have super user account for this purpose).
- **Search** - User is able to search for any particular item he/she is looking for. if such an item exist, user will see it otherwise he/she will be redirected to All products page.
- **Purchase Button** - By clicking on this button which is located at home page (main page), user will get to the product page.
- **Add, Edit and Remove products** - Site owner can add or remove any item from the website but he/she needs to have super user account and then login to his/her account.
Then, she/he can add by clicking on **Manage Products**, and remove or edit any product from the product page.
- **Admin page** - Only site owner has access to this page, he/she can login and monitor all the purchases and products.

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
14. In **Config Vars** add **AWS_ACCESS_KEY_ID**, **AWS_SECRET_ACCESS_KEY**, **DATABASE_URL** its value is the Postgres link from Heroku, **EMAIL_HOST_PASS**, **EMAIL_HOST_USER** its value is the email and you have created for this purpose,
**SECRET_KEY** you can get secret key by searching **secretkey generator** in google, **STRIPE_PUBLIC_KEY**, **STRIPE_SECRET_KEY**, **STRIPE_WH_SECRET**, **USE_AWS** its value must be True.
15. Now go back to **Deploy** tab and click on **Enable Automatic Deploys**.
16. Now click on **Deploy Branch**
17. It will take a minute and display a message that **Your app was successfully deployed**.
18. Click on **View** to launch your deployed app.

## Important

To learn how to use these IDs, and Keys, please search in google or youtube. You will find many easy and helpfull guides.

In order to have **AWS_ACCESS_KEY_ID** and **AWS_SECRET_ACCESS_KEY** you need to create and account in Aws.Amazon.com
In order to have **EMAIL_HOST_PASS**, **EMAIL_HOST_USER** you need to have google account.
In order to have **STRIPE_PUBLIC_KEY**, **STRIPE_SECRET_KEY**, **STRIPE_WH_SECRET** you need to have stripe account.

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

