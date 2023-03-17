---
title: Version Control Systems
subtitle: Here you can get acquainted with the git version control system. Here is the necessary information for working with git

# Summary for listings and search engines
summary: Here you can get acquainted with the git version control system. Here is the necessary information for working with git

# Link this post with a project
projects: []

# Date published
date: '2023-03-17T00:00:00Z'

# Date updated
lastmod: '2023-01-17T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - 吳恩達

tags:
  - Academic
  - 开源

categories:
  - Demo
  - 教程
---

```python
import libr
print('hello')
```

## Version Control Systems

Version Control Systems (VCS) are used when several people work on one project. Usually, the main project tree is stored in a local or remote repository, to which access is configured for project participants. When making changes to the project content, the version control system allows you to fix them, combine changes made by different project participants, roll back to any earlier version of the project, if required.

In classical version control systems, a centralized model is used, assuming the presence of a single repository for storing files. Most version control functions are performed by a special server. The project participant (user) receives the version of files he needs before starting work through certain commands. After making changes, the user places the new version in the repository. At the same time, previous versions are not deleted from the central repository and you can return to them at any time. The server can save not the full version of the modified files, but perform so-called delta compression — save only changes between successive versions, which reduces the amount of data stored.

Version control systems support the ability to track and resolve conflicts that may arise when several people work on a single file. You can merge (merge) changes made by different participants (automatically or manually), manually select the desired version, cancel the changes altogether or lock files for modification. Depending on the settings, the lock does not allow other users to get a working copy or prevents changing the working copy of the file by means of the OS file system, thus providing privileged access to only one user working with the file.

Version control systems can also provide additional, more flexible functionality. For example, they can support working with multiple versions of a single file, keeping a common history of changes up to the point of branching versions and their own change histories of each branch. In addition, information is usually available about which of the participants, when and what changes were made. Usually this kind of information is stored in the change log, access to which can be restricted.

Unlike the classical ones, in distributed version control systems, a central repository is not mandatory.

Among the classic VCS, the most famous are CVS, Subversion, and among the distributed ones — Git, Bazaar, Mercurial. The principles of their work are similar, they differ mainly in the syntax of the commands used in the work. 

## Git 

Git is a console utility for tracking and maintaining the history of file changes in your project. It is most often used for code, but it is also possible for other files. For example, for pictures - useful for designers.

With Git-a, you can roll back your project to an older version, compare, analyze, or merge your changes into the repository.

A repository is a repository of your code and the history of its changes. Git works locally and all your repositories are stored in specific folders on your hard drive.

Your repositories can also be stored on the Internet. Usually three services are used for this:

- GitHub

- Bitbucket

- GitLab

Each save point of your project is called a commit. Each commit-a has a hash (unique id) and a comment. A branch is assembled from such commits. A branch is a history of changes. Each branch has its own name. A repository can contain several branches that are created from other branches or merged into them.





