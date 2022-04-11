# Getting started

## How to run a project
1. checkout hexo-source branch
2. npm install
3. start hexo server 
```bash
hexo server
```

## How to create a new draft
1. run a command
```bash
hexo new draft {snake-case-name}
```

## How to manually deploy a project
1. generate public files
```bash
hexo generate
```
2. goto public folder and update master branch
```bash
cd ../public
git pull -r
```
3. copy files from hexo-source public folder to public
4. commit and push files to master
