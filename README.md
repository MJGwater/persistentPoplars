# Persistent Poplars #

### Team

  - __Product Owner__: Michael Dwyer 
  - __Scrum Master__: Nate Graf 
  - __Team Members__: Matt Goldwater, Samuel He

## Synopsis

This app is designed to give employees a platform to organize anonymously and effect change within their organizations.

## Development

### Dependecies

Node 7.0.0
MySQL 2.12.0
Express 4.14.0
React 15.4.1


### Installing Dependencies

All dependencies are installed via NPM. Avoid using any other task managers as they may not be compatible with webpack.

From within the root directory:

```sh
npm install
```

### Getting started

After installing dependencies, enter the following:

```sh
mysql.server start
mysql -u root -p
```
Press enter to forgo password, then from mysql shell:

```sh
CREATE database persistentPoplars;
```

Exit the mysql shell, now enter:

```sh
npm run dev
```

Now from another terminal tab you can start the server with:

```sh
npm start
```
