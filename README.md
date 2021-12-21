# jeromeza.github.io
Static resume - generated via: https://jsonresume.org/  
Browsable via: https://jeromeza.github.io or https://jerome.sheed.co.za

# to republish and clear gitpages cache - so changes are live
git commit -m 'rebuild pages' --allow-empty
git push origin master

# for easier publishing via docker
$ docker run -it -p 4000:4000 olbat/jsonresume /bin/bash
$ export RESUME_PUPPETEER_NO_SANDBOX=1
$ resume export resume.pdf --format pdf --theme /usr/lib/node_modules/jsonresume-theme-stackoverflow/
$ resume export index.html --format html --theme /usr/lib/node_modules/jsonresume-theme-stackoverflow/
