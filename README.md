# GitHub-Pages-Deploy (2022)

What is this repo? <br>
- ***This is a quick start guide to deploy a website through GitHub Pages using [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) commands.***

## Table of Contents
1. Packages & Installations Needed
2. File Structure
3. Deploying Step-by-Step
4. Updates & Other Important Notes

### 1. Packages & Installations Needed
List & Links:
- [Visual Studio Code](https://code.visualstudio.com/download) (*Or your preferred text editor.)
- [Node.js](https://nodejs.org/en/download/)
- [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) (*Command below, once Node.js is installed)
```
npm install -g npm
```
- [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)



Once everything needed is installed, and your file structure is correct,
run these commands:
```
npm init -y
npm i gh-pages
```

```
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/<username>/<reponame>
git push -u origin main
```


