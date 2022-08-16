# CS50W-Project 4-Final

## CS50 Web - Programming with Python and JavaScript. 

### Project purpose :

This website is an articles platform. This was the final project of HarvardX's CS50W course in 2022 and was built using Python, Django, Javascript ,CSS, HTML and Bootstrap.

This web application is not similar to anything we have already worked on. It's not a social media app nor an e-commerce website. In this website users will be able to read, rate, comment on those articles, and add any of them to "read later" so they can easily find them later. 


### Project Structure :

-In the Home page, users can search text in any part of articles title by typing any words in the input box, and click "Search" button.

-If users just want to read any article, they can just click "Random Article" button on the top, and they will get one random article in a particular topc. Additionally, they don't need to log in for those actions. 

-When users click on "Categories", they will be taken to a page that shows all the categories in the website. (Health, Environmental Issues, Food, Animals and Art). Each category contains number of articles related to the topic. Clicking on any of those categories will take the user to a new page which has all the related articles. 

-Logged users have the ability to create a new article and add it to the other existing articles, add article to "Read Later" where can read the article anytime later, and also they can add comments on any article in the web page.

-Also, logged user can add any article to "Read Later" where they can read it anytime by just clicking on "Read Later" in the main page of the website.


## Project Pages :

### Login Page :

This is the entry page to the website that requires user identification and authentication, regularly performed by entering a username and password combination.

<img width="1440" alt="Screen Shot 2022-08-16 at 2 50 56 PM" src="https://user-images.githubusercontent.com/95029840/184884014-12d23310-f2d8-440c-82a1-89b93c52f0f3.png">

### Register Page :

This signup page (also known as a registration page) enables users and organizations to independently register and gain access to your system. 

<img width="1439" alt="Screen Shot 2022-08-16 at 2 52 05 PM" src="https://user-images.githubusercontent.com/95029840/184884129-c3e19006-b68b-4df1-baa9-77890fd11b99.png">


### Logout Page :

This page informs the computer or website that the current user wishes to end the login session. 

### Home Page :

-In this page, you can search text in title of articles by input any word in the center input box, and click "Search" button.

<img width="1440" alt="im1" src="https://user-images.githubusercontent.com/95029840/184348451-745b9a42-c786-434c-9630-de065f73860a.png">

-In addition, if you just want to read something new, just click "Random Article" button on the top, and you will get some articles randomly. 

-There's no need to be logged in in order to do those actions. 

-I also added some Tooltips With Only CSS, using data attribute. So when the user hover on the "Search Icon", the following text will pop-up.


<img width="1440" alt="Screen Shot 2022-08-16 at 10 58 29 AM" src="https://user-images.githubusercontent.com/95029840/184840970-a6d80467-dd73-4825-bd6b-455c26ef6ae5.png">


### Categories Page :

-This page shows all the topics in the website. (Health, Environmental Issues, Food, Animals and Art). Each category contains number of articles related to the topic. Clicking on any of those categories will take the user to a new page which has all the related articles.

<img width="1440" alt="Screen Shot 2022-08-12 at 1 56 13 PM" src="https://user-images.githubusercontent.com/95029840/184349345-d80537bd-bbfb-46d6-adef-066155d3958f.png">


### Articles Page :

-In this page, you can get all the articles with title, a simple brief, the author, and the date of publishing this article.

-If the user is interested in any of those articles, he can click at the article at any place in the card, and he will be redirected to the full article page or he can just click on "Click here to read more".


<img width="1440" alt="Screen Shot 2022-08-12 at 1 58 46 PM" src="https://user-images.githubusercontent.com/95029840/184350596-7044017e-f395-4d4f-9b3a-76398faa9f42.png">

### Article Page :

-In the article page, the user will be able to see all the details about one article, such as the title, author, publish date, category of that article, and the entire text of the article. In the bottom of the page, all users can see all the comments on this particular article, who added that comment and the time of adding it.

-Only logged in users will have the ability to press "Add to Read Later" button which will allow them to add this article to "Read Later" page so they can find it easily later and read it at any time.


<img width="1427" alt="Screen Shot 2022-08-12 at 2 00 30 PM" src="https://user-images.githubusercontent.com/95029840/184350490-30654eb7-54ac-48e0-a08b-20aef46200e1.png">

-Also, logged in users can add comments on articles. Besides, each user can edit his comment. When a user clicks “Edit” for one of their own comments, the content of their comment should be replaced with a textarea where the user can edit the content of their comment. Then, the user should then be able to “Save” the edited comment, then the new comment will appear in the page.


<img width="1440" alt="Screen Shot 2022-08-12 at 5 12 00 PM" src="https://user-images.githubusercontent.com/95029840/184386190-617e0c7f-3f86-4760-9624-af203342dd96.png">



<img width="1440" alt="Screen Shot 2022-08-12 at 2 10 28 PM" src="https://user-images.githubusercontent.com/95029840/184351314-eae45bf9-0a6d-476a-8d30-ce15b151abe0.png">

-If the current logged in user is the author of the article which means he is the user who created that article, he can delete the article by pressing on "Delete" button. Clicking on that button will show a pop-up window created with bootstrap Modal to make sure that the user really wants to delete that article.


<img width="1440" alt="Screen Shot 2022-08-12 at 3 44 22 PM" src="https://user-images.githubusercontent.com/95029840/184366824-3c58f433-f4fd-453e-8062-d4c3f63ba1c2.png">


-This page also has a system of one to five stars for articles ratings, with five stars being the highest rating. Logged users have the ability to rate articles by clicking on any the star that represent their rating. When they rate the article the follwoing message will be shown under the rating system.


<img width="1440" alt="Screen Shot 2022-08-16 at 1 36 32 PM" src="https://user-images.githubusercontent.com/95029840/184871355-0e87ff35-b470-46bb-ad50-8ee611b41c2a.png">


### Read Later Page :

-In this page, users can see all the articles they added to be read later. So this will make it very easy to remember which articles they are interested in. 


### Author Page :

-This page shows some information about all authors in the website. Informations like the name of the author, short summary about him and all the articles that he published. 

<img width="1440" alt="Screen Shot 2022-08-12 at 2 47 58 PM" src="https://user-images.githubusercontent.com/95029840/184357882-dfce6ebd-bc8a-46e9-b570-a15c2ae88331.png">


### Create New Article Page :

-Only logged in users have the ability to create new articles and publish them in the website.

-The following picture shows the form that the users will submit in order to create a new article. Each article should has title, brief, and the content of the article itself. Also users should select the category of the article.


<img width="1440" alt="Screen Shot 2022-08-12 at 3 28 42 PM" src="https://user-images.githubusercontent.com/95029840/184363780-cfe2f78e-a05a-4a69-9208-bbb2a4f23ce0.png">

<img width="1440" alt="Screen Shot 2022-08-12 at 3 35 15 PM" src="https://user-images.githubusercontent.com/95029840/184364948-289849bf-cec5-46e3-8f83-e6412df219f3.png">




## Setup :

Requires Python3 and the package installer for Python (pip) to run:

- Create new migrations based on the changes in models: python3 manage.py makemigrations
- Apply the migrations to the database: python3 manage.py migrate
- Create a superuser to be able to use Django Admin Interface: python3 manage.py createsuperuser
- Run the app locally: python3 manage.py runserver
- Visit the site: http://localhost:8000

