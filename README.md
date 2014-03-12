Pooch Madness
=============
A fun and fundraising app for our furry friends.
Written in node by the Waltham MA JS meetup group

##Setup instructions:

For setting up Pooch Madness on a free Nitrous.io machine, see Nitrous Setup Instructions below.

###Install Node:
```
brew install node
```

###Install Bower:
```
npm install -g bower
```

###Install Dependancies:
```
npm install
```

###Install Bootstrap:
```
bower install bootstrap
```

###Start Server:
```
node app.js
```

##Optional

###Install Supervisor
```
npm install supervisor -g
```

###Start Server with Supervisor:
```
supervisor app.js
```

## Nitrous Setup Instructions

### Configure a Nitrous box with github
- Go to http://nitrous.io
- Sign up for an account and login
- Choose to create a nodejs box, and give it a name, i.e. username-nodejs
- At the top of the page, click the N20 status bar icon to add account settings
- Click Connect Github
- At the top of the page, click "Boxes"
- Choose your box and click "IDE" to launch the Nitrous IDE.

### Clone the pooch madness repo
- Go to github.com/statbit/pooch\_madness
- Click "Fork" to fork the repo under your own github account.
- In the Nitrous console, type:

```
git clone https://github.com/username/pooch\_madness.git workspace
```

```
cd workspace
```

```
git remote add upstream https://github.com/username/pooch\_madness.git
```

```
git fetch upstream
```

### Install pooch madness dependencies
From within the workspace directory, type:
```
npm install -g bower
```

```
npm install
```

```
bower install
```

### Run the app
```
node app.js
```

From the Nitrious Preview menu, click "Port 3000"
