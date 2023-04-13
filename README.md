
# Project Goals and Objectives
<details open>

The goal of this project is to create a web application that helps users manage their stock investments. Users can input information about their stocks, such as the quantity of shares, buying and selling prices, and purchase dates. The application will then analyze the performance of the user's investment and calculate profit and loss.

The application will display real-time stock prices and changes in price, and allow users to set up alerts via SMS or email for specific stocks. Users can also take notes on each stock to keep track of additional information and observations related to their investments.

In addition to individual stock information, the application will provide an overview of the user's investment portfolio, including profit and loss calculations. 

To ensure secure storage and easy access from any device, users can create an account and log in using their email, phone number, or social media accounts (via OAuth).
</details>

## Key Features
<details open>
-   Allow users to add information about their stocks, including buying and selling price, quantity of shares, and date of purchase
-   Provide real-time data on stock prices, including information on price changes
-   Enable users to set alerts for specific stocks and receive SMS or email notifications
-   Allow users to add notes to each stock
-   Provide an overall summary of users' investment portfolio, including profit and loss calculations
-   Offer user account creation and login using email, phone, or social media accounts via OAuth
</details>


## Quick Start
<details open>
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
</details>
