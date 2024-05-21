# @robertakarobin/util-starter

This is a starter repo for projects based on [@robertakarobin/util](https://github.com/robertakarobin/util).

## Usage

You probably don't want to fork this repo: you just want the files, and not all the Git history:

```sh
curl -L https://github.com/RobertAKARobin/util-starter/archive/refs/heads/main.zip > starter.zip # Download GitHub's .zip of this repo
unzip starter.zip
rm starter.zip # Don't need the zip file anymore
mv util-starter-main myproject # Rename to your project's name
cd myproject
git init # Start a new Git history
git add .
git commit -m "Initialized from RobertAKARobin/util-starter"
```
