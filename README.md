
# Style checker for CSE11 class

## How to run

* Make a clone
 
```
$ cd ~
$ git clone https://github.com/UltimatePea/CSE11StyleChecker
```

####Note: After cloning, the folder name will be either CSE11StyleChecker-master or just CSE11StyleChecker

* Change file permission if necessary

```
$ chmod u+x ~/CSE11StyleChecker-master/stylecheck
OR
$ chmod u+x ~/CSE11StyleChecker/stylecheck
```





* Check any java file

```
$ cd pa8;
$ ~/CSE11StyleChecker-master/stylecheck Snake.java
OR
$ ~/CSE11StyleChecker/stylecheck Snake.java
```

* Check all java file

```
$ ~/CSE11StyleChecker-master/stylecheck *.java
OR
$ ~/CSE11StyleChecker/stylecheck *.java
```
#### Note: If you are not using one of the lab computers, you need to set python interpreter by changing the first line of the code, or to prepend the command with "python"

* Check any java file

```
$ cd pa8;
$ python ~/CSE11StyleChecker-master/stylecheck Snake.java
OR
$ python ~/CSE11StyleChecker/stylecheck Snake.java
```

* Check all java file

```
$ python ~/CSE11StyleChecker-master/stylecheck *.java
OR
$ python ~/CSE11StyleChecker/stylecheck *.java
```

## Install

### Edit bash path to include following file

* Copy stylecheck script to binary folder

```
$ cp ~/CSE11StyleChecker-master/stylecheck ~/bin/
OR
$ cp ~/CSE11StyleChecker/stylecheck ~/bin/
```

* Add path to bashprofile

```
$ echo "export PATH=$PATH:$HOME/bin" >> ~/.bash_profile
```

* After installation, check any file by typing "stylecheck" directly

```
$ cd pa8;
$ stylecheck *.java
```


## Contribute

There is still a lot of space for improvement, e.g. file header checkings, method header checkings, e.t.c. Pull Requests are welcomed.

###There are still plenty of issues. If you happen to find some bugs, please do not hesitate to open a discussion on the issues page.


