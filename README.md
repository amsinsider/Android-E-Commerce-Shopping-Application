# Project Proposal

I am planning on designing and implementing an e-Commerce shopping application in Android that will allow end-users to register, login to the app and browse for products in different category sections. 

This application will currently have 4 pages of product categories that users can browse through and they are Sports & Outdoors, Tech, Clothing and DIY and once the users have chosen the products that they wish to purchase from category X, they can add it to their basket and proceed to the checkout. Customers can view the products added to the basket.

Before browsing for products, users are required to register and login into their account.

The main scope of this application is to allow end-users to shop for products in different categories, very similar to Amazon’s application.

After registration customers will receive a notification saying that they have registered successfully and the data from the registration will get sent to a back-end database. I will be making use of the Firebase Service to store the user’s registration data.

When customers have decided on what they want to purchase they can add the products to their basket and the users can view their basket in the form of a list view.

Users will be presented with a payment form where they are prompted to fill out their payment information and pay for the products chosen. After the payment is complete and processed users will receive an invoice through e-mail.

Each category with products will be shown on different activity pages on the application. For example, on page 1 the sports and outdoors category section will be displayed with the products available in stock etc.

I will be making use of version control using Git in order to track the changes made to the project and to also commit and push new changes when developing the application. In case I lose my work, I can revert back to previous commits to start from that checkpoint.

My initial inspiration for choosing this type of application was from the Amazon application.
I will be also making use of some Agile approaches such as Kanban Boards, Product Backlogs and Sprint Boards.

# Feasibility Study - Version 1.1 :open_file_folder:
In this section I will be writing about the different kinds of feasibility studies that will impact this project. These will determine whether this project is feasible enough to develop or not.

# Legal Feasibility :office:
Under the Copyright Design and Patents Act, all of the images and source code that I will be using throughout this project I will reference in an index at the end of the project.

Under the Data Protection Act all of the registration data will get stored in a secure back-end database using Firebase.

Under the Computer Misuse Act, I will not any malware that will harm and render other people’s computer unavailable.

# Schedule Feasibility
The total time taken for each task will be stated in a Gantt Chart and also the start and end dates for that task. The Gantt Chart will also show whether or not that task has been completed or if it’s still pending.

# Economic Feasibility
I will not be purchasing any software in order to achieve project completion, all of the software and tools that I will be using to develop this project will be free to use. No costs will be incurred.

# Technical Feasibility
I will be making use of my MacBook Pro to develop my project. The software that will be used are:

>	Android Studio: Where I will implement the User Interface 

>	Draw.io: Used to design the class diagrams using UML.

>	Zube: Used to implement Kanban Boards & implement the sprints for the project.

>	Firebase: Used to store the registration details of the customers.

>	Adobe XD CC: Used to design the User Interface of the application.

>	Survey Monkey: Used to gather data from end-users by creating a survey of 10 questions.

# Data Gathering - Questionnaire

The images below shows a Questionnaire that I have created which asks the public what they would like to see from the application.

# Figure 1

<img width="884" alt="Question 1" src="https://user-images.githubusercontent.com/29733613/75634775-76bfda80-5c08-11ea-827d-820f89a1299f.png">

# Figure 2

<img width="894" alt="Question 2" src="https://user-images.githubusercontent.com/29733613/76161846-23c9b400-612f-11ea-9d05-060657f011f1.png">

# Figure 3

<img width="899" alt="Question 3" src="https://user-images.githubusercontent.com/29733613/76161848-262c0e00-612f-11ea-8bea-9e1af4911da0.png">

# Figure 4

<img width="900" alt="Question 4" src="https://user-images.githubusercontent.com/29733613/76161850-27f5d180-612f-11ea-876d-4d5771868f44.png">

# Figure 5

<img width="899" alt="Question 5" src="https://user-images.githubusercontent.com/29733613/76161851-2a582b80-612f-11ea-8ec7-e7044f2b060d.png">

# Figure 6

<img width="898" alt="Question 6" src="https://user-images.githubusercontent.com/29733613/76161853-2cba8580-612f-11ea-8148-35428a183ad3.png">

# Figure 7

<img width="903" alt="Question 7" src="https://user-images.githubusercontent.com/29733613/76161854-2f1cdf80-612f-11ea-9652-8a896939c353.png">

# Figure 8

<img width="901" alt="Question 8" src="https://user-images.githubusercontent.com/29733613/76161884-6be8d680-612f-11ea-9b7c-16a0ad0f2e40.png">

# Figure 9

<img width="899" alt="Question 9" src="https://user-images.githubusercontent.com/29733613/76161886-70ad8a80-612f-11ea-99e3-f28ec040a7bf.png">

# Figure 10

<img width="902" alt="Question 10" src="https://user-images.githubusercontent.com/29733613/76161887-730fe480-612f-11ea-8523-e41113c10866.png">

# Requirements Specification (Product Backlog)

> **1. The main activity will have a Register Button and a Login Button below the text.**

> **2. The registration activity will have entry fields for Username, E-mail Address, Password and a terms and conditions check box that must be ticked before registering successfully.**

>   **3.   The registration activity entry fields will get validated against:**

>   **4.   Username must not be empty**.
    
>   **5.   Username ***must contain numbers**.
    
>   **6.   Username Length ***must not exceed 10 characters**.
    
>   **7.   Password Data Input Field ***must contain numbers, special characters, characters and must not be left empty.**
    
>   **8.   Password Data Input Field: Must start with an uppercase character**
    
>   **9.   E-mail Address Data Input Field: Must have an @ symbol and should not be left empty.**
    
>   **10.  E-mail Address Data Input Field: Must be within the range of [A-Z], [0-9].**
    
>   **11.  Terms and Conditions Check Box ***must be ticked to register successfully.**
      
>   **12. The Main Activity will have a drop-down menu that allows users to choose which category of products they would like to choose from. The options are:**

 >  **Sports and Outdoors.**
 
 >  **Tech.**
 
 >  **Clothing.**
 
  > **DIY.**
      
> **5. The main activity will have a Contact Us button that will allow users to fill out a form if they are having any issues with the application. SQLite will be used as the database to store any complaints from users.**

> **6. Users will receive a notification saying that they have registered successfully after clicking the register button.**

7. The login activity will allow users to login with their E-mail Address and password only.

8. After users register with their unique account, ***Firebase*** will be used to store the credentials in a back-end database.

9. A toast message will appear saying “You are logged in as X” when the user has logged in successfully.

10. The ***Sports & Outdoors activity*** will show the images of the products that are currently in stock. There will be 2 pages of sports & outdoors products.

11. The ***Tech category*** activity will show the images of the products that are currently in stock.

12. The ***Clothing category*** activity will show the images of the products that are currently in stock.

13. The ***DIY category** activity will show the images of the products that are currently in stock.

14. The cost of each product will be displayed next to the images in GBP.

15. Users have the option to choose the quantity of each product, hence that will affect the total cost of the product.

16. There will be an “Add to Basket” button underneath the products which allows the users to add the chosen product(s) to their basket (adds it to the menu items).

17. The Clothing products will have an option where users can choose the size, color and quantity they would like to pick.

18. Users have the option to view the products in their basket by clicking “View Basket” which will get placed in a menu on the activity.

19. On each of the categories, users will have the ability to choose the color of the product that they would like.

20. The application will have a Payment activity that will have the following entry fields when checking out:

    -	***The type of payment the users may wish to pay with: VISA, PayPal, Mastercard.***
    
    -	***Card number: XXXX XXXX XXXX XXXX (will get validated to ensure that only numbers are present) and no characters are inputted.***

    -	***Card CVV (* this is the 3-digit code at the back of the card), will get validated to ensure that no more than 3 numbers are entered.***
    
    -	***Cardholder’s Name.***
    
    -   ***Expiry Date (Month & Year) in the form of drop-down menus (Spinners).***

20. The payment activity will have a ***“Confirm Payment”*** button that the users will click when they are ready to pay for the products.

21. A rotating circular progress bar will be shown after the button has been clicked to indicate that the payment is being processed and after it has been complete, an alert dialogue will get displayed saying that the payment has been successful.

22.	After the payment has been completed, the users will get re-directed back to the home page.


# Homepage Implementation

> ***How does it work?***

This is how the Homepage of the application looks like. Users who are on the application will be able to register an account by pressing the register button, then they will be taken to a form to fill out their details, after that they will be re-directed to the login page where they should login their account.

If users are having any issues then they can fill out a form on the Contact Us section of the app.

<img width="329" alt="Homepage" src="https://user-images.githubusercontent.com/29733613/78153565-1accb980-7433-11ea-801b-217c7dd359eb.png">

# Register Implementation

> ***How does it work?***

This is the Register activity of the application. Users can create an account by choosing a Username, Password and their e-mail. Once users click the Register button, they will receive a notification saying that they have registered successfully and the details will get written to a firebase database.

<img width="332" alt="Register UI" src="https://user-images.githubusercontent.com/29733613/78153578-1e604080-7433-11ea-80ea-7b59849d0388.png">

# Login Implementation

> ***How does it work?***

This is how the Login Activity looks like. Users are required to log in with their registered e-mail address and password, the details must match with the ones they have registered with, otherwise they won't be granted access.

<img width="331" alt="Login" src="https://user-images.githubusercontent.com/29733613/78170576-0b596a80-744b-11ea-8db3-26627685f06a.png">

# Tech Activity Implementation

> ***How does it work?***

This is how the Tech Category Activity looks like. Users are able to choose a quantity, colour and size for each of the product and then add the product to the basket just like Amazon's shopping application. There is however a small issue, whenever a colour, quantity or size is chosen, it doesn't show up in the drop-down menu, this will be fixed in a later update.

<img width="336" alt="Tech Activity" src="https://user-images.githubusercontent.com/29733613/78153589-20c29a80-7433-11ea-8f24-eed4b3105e3c.png">
