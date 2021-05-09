# IS219_Express-JWT-Authentication

### To make this authentication page work follow these steps
1. Clone the Repo
2. Run the command: npm install
3. Run the command: node auth.js
4. Open up postman and put the right parameters to test the app

### Logged in User looks like this
![image](https://user-images.githubusercontent.com/30082380/117577826-6b442b00-b0b9-11eb-9408-a295b122850f.png)

### Books page looks like this if taken these steps 
1. Run the command: node books.js 
2. Open up postman and put the right parameters to test the app and make sure it is a get request
3. Go to Headers and add a Key called "Authorization" and accessToken of the logged user that you had in this format:
"Bearer " + accessToken
![image](https://user-images.githubusercontent.com/30082380/117578325-caa33a80-b0bb-11eb-8bb8-ec891052784b.png)
