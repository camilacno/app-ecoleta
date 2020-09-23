
<h1 align="center">  
<img alt="Ecoleta" src="https://github.com/camilacno/app-ecoleta/blob/master/ecoleta-web/src/assets/mockup.png" />  
</h1>

<p align="center">
	<img alt="Node.js" 
src="https://img.shields.io/badge/nodejs-green?labelColor=green&logo=node.js&logoColor=white"> 
<img alt="ReactJS" src="https://img.shields.io/badge/reactJS-6cf?logo=react&logoColor=white&labelColor=007ACC">  
<img alt="React Native" src="https://img.shields.io/badge/reactnative-6cf?logo=react&logoColor=white&labelColor=007ACC">  
  <img alt="Typescript" src="https://img.shields.io/badge/typescript-informational?labelColor=blue&logo=typescript&logoColor=white"> 
  <img alt="Git" 
src="https://img.shields.io/badge/git-grey?labelColor=greu&logo=git&logoColor=white"> 
</p>

<p align="center">
	<img alt="expo" 
	src="https://img.shields.io/badge/expo-white?labelColor=grey&logo=expo&logoColor=white">
		<img alt="sqlite" 
	src="https://img.shields.io/badge/sqlite-blue?labelColor=blue&logo=sqlite&logoColor=white">

</p>

<p align="center">
	 <img alt="Mode" src="https://img.shields.io/badge/mode-development-orange">  
	<img alt="License" src="https://img.shields.io/github/license/camilacno/proffy-web">    
  <a href="https://www.linkedin.com/in/camilacno" target="_blank"> 
    <img src="https://img.shields.io/badge/-camilacno-007ACC?logo=linkedin&logoColor=white&labelColor=007ACC" alt="Developer LinkedIn" />
</p>

## About the Application

**Ecoleta** is a way to connect companies and entities that collect organic and inorganic waste to people who need to dispose of their waste in an ecological way.

This v1.0 of the application was developed during **Next Level Week #1**, a project from Rocketseat.

###### *Go to <a href="#content">Content</a>*.
<br>

## Content

 - <a href="#about-the-application">About the Application</a>
 - <a href="#main-libs">Main libs</a>
 - <a href="#how-to-run">How to run</a>
    - <a href="#api">Server</a>
    - <a href="#web">Web</a>
    - <a href="#mobile">Mobile</a>
    
<br/>

## Main Libs

[React Navigation](https://reactnavigation.org/) | [Express](https://expressjs.com/pt-br/) | [KnexJS](http://knexjs.org/) | [SQLite3](https://www.sqlite.org/index.html) | [Postgres](https://www.npmjs.com/package/pg) | [Axios](https://github.com/axios/axios)  | [Leaflet](https://leafletjs.com/) | [Nodemailer](https://nodemailer.com/about/) | [Expo Google Fonts](https://github.com/expo/google-fonts) | [Picker Select](https://github.com/lawnstarter/react-native-picker-select) | [Multer](https://github.com/expressjs/multer) | [Celebrate](https://github.com/arb/celebrate)
 
[EditorConfig](https://editorconfig.org/) | [ESLint](https://eslint.org/) | [Prettier](https://prettier.io/)
	
###### *Go to <a href="#content">Content</a>*.
<br/>

## How to run

### Requirements
- **[Node.js](https://nodejs.org/en/)**  
- **[Git](https://git-scm.com/)**  
- **[NPM](https://www.npmjs.com/)**  or  **[Yarn](https://yarnpkg.com/)**.
- **[Expo](https://expo.io/)**  

### Server

##### Cloning
```bash
$ git clone https://github.com/camilacno/app-ecoleta-server.git
```
 ##### Installing dependencies
   ```bash
$ yarn # or npm install
```
  
 ##### Database setup and tables creation
  ```bash
$ yarn knex:migrate # or npm run knex:migrate
```
  
  ##### Start API
  ```bash
$ yarn start # or npm run dev
```
<br>

### Web

##### Cloning
```bash
$ git clone https://github.com/camilacno/app-ecoleta-web.git
```
 ##### Installing dependencies
   ```bash
$ yarn # or npm install
```
  
 ##### Start web application
 ```bash
$ yarn start # or npm start
```
<br>

### Mobile

##### Cloning
```bash
$ git clone https://github.com/camilacno/app-ecoleta-mobile.git
```
 ##### Installing dependencies
   ```bash
$ yarn # or npm install
```
  
 ##### Start mobile application
 ```bash
$ yarn start # or expo start
```
###### *Go to <a href="#content">Content</a>*.
