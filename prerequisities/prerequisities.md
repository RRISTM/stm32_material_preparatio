# Tools needed

List of tools which we use:

## 1. git

Version control system. Used to backup content, and cooperation sharing

## 2. Visual Studio Code

Popular editor, with embedded git client and lot of extentions

## 3. ScreenToGif / Sharex

Tools to capture screen and store it as video or animated image
## 4. Github account

site where is possible host git repositories

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

# Visual Studio Code (VS)

We will use visual studio code. Very nice advanced editor with loat of extensions.
[Link](https://code.visualstudio.com/)

## Add extentions

1. Run VS
2. Open extension tab
   
![Git extentions](./img/02.png)   

3. Install GitGraph

It will graphically show git tree structure

![Git Graph](./img/001.png)

4. Markdown All in One

This extention can show markdown preview

![Markdown all in one](./img/002.png)

# Screen to gif

Download and install

[Link](https://www.screentogif.com/)

# Sharex

Download and install

[Link](https://getsharex.com/)

# Github

Create a github account

[Link](https://github.com/)

If neede PC tool can be also used

[Link](https://desktop.github.com/)

