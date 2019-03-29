# FLASK-REACT - Google Vision API

## Python, Flask, React, MongoDB

- Get your project started in no time with Python, Flask, React, Redux, m-lab, Google Auth authentication, Sass/SCSS styling, Jest & Enzyme unit testing, Heroku deployment and more.

### Technologies:

#### Server Side

- Python3
- Flask
- OAuth2
- JWT

#### Client Side

- ReactJS
- Redux
- Webpack
- Babel
- Axios
- Sass
- BootStrap 4
- jQuery
- Font Awesome

#### Database

- MongoDB
- m-Lab

#### Unit Test

- Jest
- Enzyme
- React Test Renderer

---

### Server Configuration:

1. Proxy :
   - use "proxy": "http://localhost:5000", in 'package.json', making sure that the port = the backend server's port on /server/app.py = devserver.proxy in /webpack.config.js

### Installation

#### BackEnd

1. Install [Python 3.6](https://www.python.org/downloads/)
2. Install and activate [Python virtualenv](https://virtualenv.pypa.io/en/stable/), (recomended).
   ```
   pip3 install virtualenv
   cd <project folder>
   python3 -m virtualenv ./venv
   source ./venv/bin/activate
   ```
3. Install Requirement
   ```
   pip install requirements.txt
   ```

#### FrontEnd

1. Install [Node](https://nodejs.org/en/)

2. Install the required packges
   Run 'npm install' or 'npm i' to install the required packages.
   ```
   cd client/
   npm install
   ```

---

### Running the Dev Server:

1. from the root '/ ' Navigate to server/
   ```bash
   cd server/
   ```
1. Run app.py
   ```bash
   python app.py
   ```
1. With the server runing, open a new bash terminal and navigate to client from the root '/ '

   ```bash
   cd client/
   ```

1. Front-End Server (Webpack)
   ```
   npm run dev-server:client
   ```

- Open your browser at port 8080 => [http://localhost:8080](http://localhost:8080)

4. Unit Testing Server (Jest, Enzyme)
   ```
   npm run test
   ```

---

### Deployment

#### Heroku:

- This boilerplate is configured to run at Heroku with no need for further configuration.

1. Go through the traditional [Heroku-Cli setup](https://devcenter.heroku.com/articles/heroku-cli).
2. At the root level of the project
   ```
   heroku create
   ```
3. push to Heroku
   ```
   git push heroku master
   ```

---

## API END-POINTS:

### USERS : /api/users

---

## Third party Packages Usage Examples :

---

## Next Steps:
