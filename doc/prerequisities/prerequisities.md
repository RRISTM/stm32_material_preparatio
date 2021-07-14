# Tools needed

List of tools which we use:

1. git
2. node.js
3. Visual Studio Code
4. yarn
5. ScreenToGif
6. Github account

# Git

Versoning control system. Used to version our work and publish our code on github
[Link](https://git-scm.com/)

## Setup credentials

To be able recognize who created commit

```
git config --global user.name "Mona Lisa"
git config --global user.email "Mona@Lisa.com"
```

## Setup proxy

We need to setup proxy to be sure that we cann access github

```
git config --global http.proxy http://proxyUsername:proxyPassword@proxy.server.com:port
git config --global http.sslVerify false
```

```
git config --global https.proxy http://proxyUsername:proxyPassword@proxy.server.com:port
git config --global https.sslVerify false
```

In our case:
'http://firstName%20lastName:password@appgw.sgp.st.com:8080'

'%20' is space
Password in my case '.' od ok. But ',' must be in format '%2C'

This should guarantee that git can reach github

# Node js

Node js is runtime enviroment.
We need it for the website build.

Download and install LTS version

[Link](https://nodejs.org/en/)

Second part is present of 'npm'. Which is package manager used to download js packages. 

## Configure npm proxy

Similar to git we must set npm proxy.

```
npm config set proxy http://USERNAME:PASSWORD@PROXY_ADDRESS:PROXY_PORT
npm config set https-proxy http://USERNAME:PASSWORD@PROXY_ADDRESS:PROXY_PORT
```

In our case 
`http://firstName%20lastName:password@appgw.sgp.st.com:8080`

'%20' is space
Password in my case '.' od ok. But ',' must be in format '%2C'

Use sommand 2x for http and https. 

# Visual Studio Code (VS)

We will use visual studio code. Very nice advanced editor with loat of extensions.
[Link](https://code.visualstudio.com/)

## Add extentions

1. Run VS
2. Open extension tab
   
![Git extentions](../img/02.png)   

3. Install GitGraph

It will graphically show git tree structure

![Git Graph](../img/001.png)

4. Markdown All in One

This extention can show markdown preview

![Markdown all in one](../img/002.png)

# Yarn

Yarn is pure package manager paralell to npm.

[Link](https://classic.yarnpkg.com/en/docs/install/#windows-stable)

Yarn is installed over npm. So now we van cest it. 

## Add Yarn

1. Open VS code. 
2. Open terminal

![Open terminal](../img/03.png)

3. Install yarn over npm

```
npm install --global yarn
```

4. Check instalation by version check

```
yarn --version
```

## Configure Yarn proxy

Same as for npm, we must configure our proxy.

```
yarn config set proxy http://username:password@host:port
yarn config set https-proxy http://username:password@host:port
```

In our case you can use quation now(i know here it is working)
`"http://firstName lastName:password@appgw.sgp.st.com:8080"`


# Screen to gif

Download and install

[Link](https://www.screentogif.com/)

# Github

Create a github account
[Link](https://github.com/)



