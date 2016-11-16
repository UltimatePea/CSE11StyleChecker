
# Style checker for CSE11 class

## How to run

* Make a clone
 
```
$ cd ~
$ git clone https://github.com/UltimatePea/CSE11StyleChecker
```

* Change file permission if necessary

```
$ chmod u+x ~/CSE11StyleChecker-master/stylecheck
```

* Check any java file

```
$ cd pa8;
$ ~/CSE11StyleChecker-master/stylecheck Snake.java
```

* Check all java file

```
$ ~/CSE11StyleChecker-master/stylecheck *.java
```

## Install

### Edit bash path to include following file

* Copy stylecheck script to binary folder

```
$ cp ~/CSE11StyleChecker-master/stylecheck ~/bin/
```

* Add path to bashprofile

```
$ echo "export PATH=$PATH:$HOME/bin" >> ~/.bash_profile
```

## Contribute

There is still a lot of space for improvement, e.g. file header checkings, method header checkings, e.t.c. Pull Requests are welcomed.



