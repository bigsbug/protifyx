
# Project Goals and Objectives

The purpose of this project is to develop a web application that enables users to track their stock investments. The application should allow users to add information about the stocks they own, including the quantity of shares they hold, the buying and selling price, and the date of purchase. Additionally, the application should provide users with an analysis of their investment performance, including profit and loss calculations.

The application should provide users with real-time data on their stock prices, including information on how much the prices have gone up or down. Furthermore, the application should enable users to set alerts for specific stocks so that they receive SMS or email notifications when the prices rise or fall beyond a certain level.

The application should allow users to add notes to each stock, enabling them to track any additional information or observations related to their investments. Additionally, the application should provide users with an overall summary of their investment portfolio, including their profit and loss calculations.

Finally, the application should offer users the ability to create an account and log in using their email address, phone number, or social media accounts (via OAuth). This will ensure that the user's investment data is stored securely and that they can access it easily from any device.

## Key Features

-   Allow users to add information about their stocks, including buying and selling price, quantity of shares, and date of purchase
-   Provide real-time data on stock prices, including information on price changes
-   Enable users to set alerts for specific stocks and receive SMS or email notifications
-   Allow users to add notes to each stock
-   Provide an overall summary of users' investment portfolio, including profit and loss calculations
-   Offer user account creation and login using email, phone, or social media accounts via OAuth



## Quick Start

1.  Clone the repository and navigate to the project directory.
    
    Copy code
    
    `git clone https://github.com/bigsbug/protifyx.git`
    
    `cd protifyx` 
    
2.  Create a copy of the `.env.sample` file and rename it to `.env`.
    
    Copy code
    
    `cp .env.sample .env` 
    
3.  Edit the `.env` file and replace the values of `SECRET_KEY` and `DATABASE_URL` with your own values.
    
    
    `DEBUG=on
    SECRET_KEY='your-secret-key'
    DATABASE_URL='your-database-url'
    CACHE_URL=dummycache://` 
    
4.  Install the project dependencies using pip.
    
    Copy code
    
    `pip install -r requirements.txt` 
    
5.  Run the database migrations to set up the initial schema.
    
    Copy code
    
    `python manage.py migrate` 
    
6.  Create a superuser account to access the Django admin site.
    
    Copy code
    
    `python manage.py createsuperuser` 
    
7.  Start the Django development server.
    
    Copy code
    
    `python manage.py runserver` 
    
8.  Open your web browser and navigate to [http://localhost:8000](http://localhost:8000/). You should see the home page for your Django app.
    
9.  Log in to the admin site at [http://localhost:8000/admin/](http://localhost:8000/admin/) using your superuser credentials to access the admin interface.
    

That's it! You should now have a working Django app up and running on your local machine, with your sensitive information securely stored in the `.env` file
