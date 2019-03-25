# wp-build #
Code based on https://v4-alpha.getbootstrap.com/examples/narrow-jumbotron/

Delete all local files and folders except php.ini and the c9 folder and then enter the following in your bash terminal
```sh
$ git init
$ git remote add mrc git@github.com:zeromile/wp-build.git
$ git pull src master
$ git remote rm mrc
$ git remote add origin git@github.com:USERNAME/wp-build.git
$ git add .
$ git commit -m “new version”
$ git push origin master
```