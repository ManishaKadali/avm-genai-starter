# Getting Started with the AVM Hackathon 

### Readme Files for all use cases be found [here](https://github.com/addvaluemachine/avm-genai-hackathon-usecases)

Team 1	54.211.23.29 </br>
Team 2	52.2.140.230</br>
Team 3	3.91.77.112</br>
Team 4	3.90.155.244</br>
Team 5	3.82.64.179</br>
Team 6	3.91.236.185</br>
Team 7	54.205.202.58</br>
Team 8	3.90.224.162</br>
Team 9	54.224.105.175</br>
Team 10	35.170.50.254</br>
Team 11	54.236.15.167</br>
Team 12	18.212.111.25</br>
Team 13	54.224.17.36</br>
Team 14	54.221.86.252</br>



## Those with Amazon Linux Machines.
######connect to the box
ssh ec2-user@54.166.146.10 -i hk1.pem

######execute the following commands
sudo su
yum install git npm
git clone https://github.com/addvaluemachine/avm-genai-starter
cd avm-genai-starter/

npm config set legacy-peer-deps true
npm install
npm start



#
# Install Prerequisites
* ### Have git installed - if you want to use the terminal for git commands, otherwise you can also donwload the zip file of the hackathon repository. Guide to install git [here](https://github.com/git-guides/install-git)
* ### Have node.js installed, if you do not have it installed visit the  [official Node.js page](https://nodejs.org/en/download/) and download it. We recommend downloading the version [v20.4.0](https://nodejs.org/dist/v20.4.0/)
* ### Have npm installed - it will come installed with node.js

#

### Possible errors
If you run into any problems during the `npm install` `npm start` steps.
It is likely due to the installed npm version, you might have to downgrade it. Fixes:

### Fix: 1
- run ```npm config set legacy-peer-deps true```
- now you can repeat the `npm install` `npm start` steps

### Fix: 2    
- use ```nvm``` (Node Version Manager), instruction for installation found [here](https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating)
- run `nvm use`, it will try and use the version specified in the ```.nvmrc``` file, if the required version is not installed on your machine, it will provide you the steps required for downloading it (```nvm install v20.4.0```). After you downloaded it, run `nvm use` again
- now you can repeat the `npm install` `npm start` steps.



## Available Scripts
Navigate to the project directory, you can run:
### `npm install`
### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.



## Those with Amazon Linux Machines.
######connect to the box
ssh ec2-user@54.166.146.10 -i hk1.pem

######execute the following commands
sudo su
yum install git npm
git clone https://github.com/addvaluemachine/avm-genai-starter
cd avm-genai-starter/

npm config set legacy-peer-deps true
npm install
npm start




##You wont need the below commands##
### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!


