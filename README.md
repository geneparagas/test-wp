# Restaurant-app

Build a simple webapp that allows the user to filter for restaurants open by date time as well as restaurant name. On top of that, users can save restaurants into their own named collections (eg. Vegetarian favourites, Meat-lovers etc.). Users can also invite their friends to collaborate (add, remove, edit name) on the collections via email, and they can see updates to their collections in real-time, without page refreshes.

## Briefs

This Project is created using React and Redux for the Frontend Express for Backend

## Built With
* React & Redux - Frontend client side rendering
* Express - backend supporting the nodemailer to get the data from axios and also google api
* Firebase - Database storing all the data from the project and because of the realtime data and cloud support (Cloud Firestore)
* Nodemailer - free email provider using my personal gmail API and also get easy rendering data for Express
* Materialize - UI design

### Installing

Download Repo using gitbash or git just copy the command below or click download zip found at the right side

```
git clone https://github.com/geneparagas/restaurant-app-gene.git
```

once done open the file and then open the cmd terminal and input the commands below

```
npm install
cd client 
npm install
```
Client folder contains the fontend development and the index.js from the root folder is the backend.

## Deployment

once finish installing the dependencies go back to the root folder

open new command terminal and then run the command below 
```
npm run dev
```
adding concurrently as a dependencies it can execute two react-scripts at the same time frontend and backend
http://localhost:3000/ 

## Explore

 🙌 This website contains array of data of restaurants and also user collections, you can easily filter both restaurants name and time,

Explain how to run the automated tests for this system

### Functions

:ballot_box_with_check: List of restaurants that can easily search both name and time.

:ballot_box_with_check: Create new Collections with your choice of name.

:ballot_box_with_check: Easy add your restaurants just press add button you can see realtime favorite list updates.

:ballot_box_with_check: Delete from your list is realtime as well.

:ballot_box_with_check: Edit your Collection's name without refreshing the page.

:ballot_box_with_check: you can also send email to a friend even in gmail or other email accounts

:ballot_box_with_check: your friend can also go to your Specific collect via link from the email

