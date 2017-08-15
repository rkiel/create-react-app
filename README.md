# create-react-app

Clone the repo

```bash
mkdir -p ~/GitHub/rkiel && cd $_
git clone git@github.com:rkiel/create-react-app.git
```

Install packages

```bash
cd ~/GitHub/rkiel/create-react-app
yarn install
```

Name your new React application

```bash
export MY_NEW_APP=next-cool-project
```

Create a new React application

```bash
cd ~/GitHub/rkiel/create-react-app
yarn run create ../$MY_NEW_APP
```

Start version control

```bash
cd ~/GitHub/rkiel/$MY_NEW_APP
git init
git add .
git commit -m "Initial commit"
```
