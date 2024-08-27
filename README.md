# maglab-main
The FORMER central public repository for the lab. The lab github is now https://github.com/comp-cogneuro-lang

## Usage

GitHub is great for:

* Sharing your code (e.g., R scripts, PsychoPy experiments)
* Asking questions about other people's code
* Asking for help with your own code
* Documenting your code
* Keeping all of your scripts in one safe place for future reference
* Keeping track of changes to your code, and undoing changes that led to problems

This Organization is a way for us to keep a bunch of repositories in one place,
  specifically organized around our lab, so that we can help each other&mdash;and
  ourselves&mdash;out.

### New to Git/GitHub?

First, you will want to [install git](https://git-scm.com/download).

Then, you'll probably want to [learn the basics of Git and GitHub](http://blog.udacity.com/2015/06/a-beginners-git-github-tutorial.html).

If you have questions, Rachael should be able to help (others with git experience,
  please feel free to add your names too!).

### Organization organization

You have a few options for posting your own code:

* You could push it to this repository.
* You could make a repository for your own code (use the "+" button in the top
  toolbar next to your icon, or go to the Organization's main page and hit "New
  Repository").
* You could make a separate repository for every project/topic/whatever. The
  organization has unlimited free public repositories.

### Asking for help

[Issues](https://github.com/uconn-maglab/maglab-main/issues) are a good way to
  ask for help or suggest improvements (even if you don't know how they would be
  implemented). You would probably open an issue on the repository where the code
  in question is hosted. You can link to the file and @mention people if you want.

### Offering help

The simplest way to offer help is to leave a comment on an issue. But sometimes,
  you'll want to edit code directly. For that, you will want to make a pull request.

A **pull request** is when you make changes to files in a repository and propose
  to the repository's owner, so that they can "pull" them in if they approve of
  the changes.

First, you'll need to **fork** the repository by clicking the "Fork" button in the
  upper right corner. Then, clone it to your computer with

```{git}
git clone https://github.com/uconn-maglab/[repo-name].git
```

Make a new **branch** for your changes: (assume "update" is the new branch name--
  but you can call it whatever you want)

```{git}
git branch update
git checkout update
```

Make your changes, commit and push them to your branch, and open a pull request (find the "Pull Requests" tab) in the original repository, explaining what you did. If the repository owner is happy with the changes, they will **merge** them into their repo. Otherwise, they might ask for more clarification or ask you to expand on it (of course, whether or not you do so is your choice).

## Things to keep in mind

Everything you post here is public. If you specifically want your code private,
  use the [maglab-private](http://github.com/cranndarach/maglab-private) repository.
  But if it's not confidential, sharing it publicly can be cool and help a lot of
  people out. Just remember that this public nature has several important implications:

1. Do not post anything that you do not want the world to see.
2. You will want to license your work so that others may adapt it on your terms
    (this is much less scary than it sounds--see below for more detail).
3. Respect others' intellectual property; do not publish anything that you did
    not create unless you *know* you have the right to do so.

### Write permissions

You technically have the right to write (push) to any repository in the organization.
  Please be decent about this and don't write to a repo that is entirely someone
  else's code without their permission. However, if you have a fork, you can totally
  write to that, and submit a pull request if you think it should be incorporated
  into the original.

### About licensing and copyright

By default, **everything you create is copyrighted to you**, with all rights
  reserved. This means that *no one* can (legally) use, modify, or distribute it without
  your express permission. That's not really ideal for collaboration.

You have the right (and are encouraged) to license your work, which is a way of
  making explicit what you permit--or do not permit--others to do with your work.
  I know it sounds like a hassle, but it's a lot simpler than you'd expect. You
  can find accessible information about licenses on [choosealicense.com](http://choosealicense.com/).

To make things even simpler, it might be best if we have a standard license that
  everyone is encouraged to use (**but you will always have the right to choose not to**).
  That way, everyone is on the same page about what is and is not okay to do, and
  you can know that your license is compatible with any scripts, etc. that you
  are using. I tentatively propose the [MIT license](http://choosealicense.com/licenses/mit/),
  which is summarized as:

1. You can use, modify, and distribute the work as long as the original copyright
  holder is properly acknowledged.
2. No warranty is provided&mdash;people can't get mad if your code breaks something of
  theirs (or, they can technically get mad, but that's all).

Regardless of what license you choose, please be cognizant of others' choices
  (that is, don't incorporate a [GPL-licensed](http://choosealicense.com/licenses/gpl-3.0/)
  file into an MIT-licensed project). A license is good for both the copyright
  holder and the user, because it creates a clear set of terms so that there will
  be no legal surprises.
