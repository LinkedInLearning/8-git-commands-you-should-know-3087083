# 8 Git Commands You Should Know 
This is the repository for the LinkedIn Learning course 8 Git Commands You Should Know. The full course is available from [LinkedIn Learning][lil-course-url].

![1667324559752](https://user-images.githubusercontent.com/25848438/200744297-16c76d19-bb0a-4ca1-9119-859077ce385b.jpeg)

If you’re a software developer, you probably already know that Git is one of the most useful version control systems out there. But while most developers have mastered the basics of Git, it can be a bit harder to take your skills to the next level and become an advanced Git user. In this course, instructor Ronnie Sheer shows you how to make the move from intermediate Git developer to the realm of finely tuned, source control expert.<br><br>Learn eight power-user Git commands that can save you time, prevent bugs, and more. Find out how to increase your productivity as well as minimize your moments of frustration. Ronnie walks you through a few basic tricks like stashing and adding changes, and then turns to more advanced techniques, such as undoing commits, reverting, and setting up precommit hooks. Test out your new skills with Git-command challenges along the way.
<br><br>This course is integrated with GitHub Codespaces, an instant cloud developer environment that offers all the functionality of your favorite IDE without the need for any local machine setup. With GitHub Codespaces, you can get hands-on practice from any machine, at any time—all while using a tool that you’ll likely encounter in the workplace. Check out the [Using GitHub Codespaces with this course][gcs-video-url] video to learn how to get started. 

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"


### Instructor

Ronnie Sheer

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/ronnie-sheer?u=104).

[lil-course-url]: https://www.linkedin.com/learning/8-git-commands-you-should-know-project-mojo-revision
[gcs-video-url]: https://www.linkedin.com/learning/8-git-commands-you-should-know-project-mojo-revision/using-github-codespaces-with-this-course

