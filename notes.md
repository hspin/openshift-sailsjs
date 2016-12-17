## sails js setup

change key in config/session.js

generate random 

1
    < /dev/urandom tr -dc _A-Z-a-z-0-9 | head -c${1:-32};echo

2

    date +%s | sha256sum | base64 | head -c 32 ; echo


git init

git remote add origin ssh://3434343@example.rhcloud.com

git add . ; git commit

git pull origin master

fix conflicts

git add . ; git commit

git push origin master
