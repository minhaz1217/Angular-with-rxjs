
## Angular wtih RxJS

In this repo I will maintain the code that I'll be doing along with the [course](https://www.udemy.com/course/rxjs-reactive-angular-course/) "Build Angular 15 Applications in Reactive style with plain RxJs - Patterns, Anti-Patterns, Lightweight State Management" by Angular University.

I will try to create a branch for every checkpoint.

What I do is that, I create a branch at the start of a tutorial and commit the changes done in that episode into that branch and after that I merge that branch to master when the episode is done.

So say if you want start code of Episode 10, then you will have to start with the branch of Episode 09, because 09 has the code from end of episode 9 and beginning of episode 10.

# Installation pre-requisites

Please use Node 18 long-term support (LTS) version.

# Installing the Angular CLI

With the following command the angular-cli will be installed globally in your machine:

    npm install -g @angular/cli 

# How To install this repository

We can install the master branch using the following commands:

    git clone https://github.com/minhaz1217/Angular-with-rxjs.git
    
This repository is made of several separate npm modules, that are installable separately. For example, to run the au-input module, we can do the following:
    
    cd Angular-with-rxjs
    npm install

Its also possible to install the modules as usual using npm:

    npm install 

NPM 5 or above has the big advantage that if you use it you will be installing the exact same dependencies than I installed in my machine, so you wont run into issues caused by semantic versioning updates.

This should take a couple of minutes. If there are issues, please post the complete error message in the Questions section of the course.

# To Run the Development Backend Server

In order to be able to provide realistic examples, we will need in our playground a small REST API backend server. We can start the sample application backend with the following command:

    npm run server

This is a small Node REST API server.

# To run the Development UI Server

To run the frontend part of our code, we will use the Angular CLI:

    npm start 

The application is visible at port 4200: [http://localhost:4200](http://localhost:4200)



# Important 

This repository has multiple branches, have a look at the beginning of each section to see the name of the branch.

At certain points along the course, you will be asked to checkout other remote branches other than master. You can view all branches that you have available remotely using the following command:

    git branch -a

The remote branches have their starting in origin, such as for example 1-navigation-and-containers.

We can checkout the remote branch and start tracking it with a local branch that has the same name, by using the following command:

      git checkout -b section-1 origin/1-navigation-and-containers

It's also possible to download a ZIP file for a given branch,  using the branch dropdown on this page on the top left, and then selecting the Clone or Download / Download as ZIP button.


# Made with <span style="color:red;">❤</span> By - [Minhazul Hayat Khan](https://github.com/minhaz1217)