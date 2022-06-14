# Git Learning Diary

### What is git

Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear.

So basically. Git keeps track of the changes a couple of people make on a single project and then merges the code where people have worked on different parts into one project. This way, when someone introduces a bug, you can track down the code that introduced the bug by going through the commits. Commits must be made to a project to tell git that you’re satisfied with the changes you’ve made and want to commit the changes to the main **branch** called **master** by default.

## How to start it?

Download git

https://git-scm.com/downloads

### Initialize a git repository 

``` git
git init
```

![git init](C:\Users\Tommy\Pictures\git init.png)

### Create a doc

It is a command to check the condition of this file, and it will find Untracked files.

```
git status
```



![git(2)](https://github.com/LilyWu0719/git/blob/master/scr/git(2).png)

It is a command to add all the untracked files.

```git
git add .
```

After you added it, you suppose to save it.

```git
git commit -m 'initial commit'
```

Subsequently,  create a path to connect your GitHub website.

``` git 
git remote add origin HTTPS
```

Overall, upload the document to your repository.

```git
git psuh -u origin master
```

## My opinion

Actually, there are several methods in git, if you want to learn more functions, you can have a look at my references

## References

https://medium.com/@onejohi/git-understanding-the-basics-ba004a20dacc

https://en.wikipedia.org/wiki/Git

https://www.youtube.com/watch?v=N6YQlPuAamw

https://medium.com/@hyWang/%E5%A6%82%E4%BD%95%E5%9C%A8%E4%B8%80%E5%8F%B0%E9%9B%BB%E8%85%A6%E4%BD%BF%E7%94%A8%E5%A4%9A%E5%80%8Bgit%E5%B8%B3%E8%99%9F-907c8eadbabf

https://medium.com/cyen6/%E5%A6%82%E4%BD%95%E4%B8%80%E5%8F%B0%E9%9B%BB%E8%85%A6%E4%BD%BF%E7%94%A8%E5%A4%9A%E5%80%8B-git-%E5%B8%B3%E8%99%9F-144d9582ff09

https://www.youtube.com/watch?v=TjHslMeJ81k&t=390s

https://www.youtube.com/watch?v=vSeYsk4WYvg
