##About Alloy

Alloy is a tool built by students at the University of Hawaii to help members of the UH iLab and sPACE communities with posting and finding projects to work on, and finding people to work with. Have an idea for a project that would look good on your resume? Want to do your own custom senior project? Or do you just want experiment and learn something new with other students who just want to do the same?

Let Alloy help you find a team that's right for what you want.

<form action="http://alloytestdeployrv.meteorapp.com/">
  <input type="submit" value="Try Alloy Now" / >
</form>

##Key Features
* Create profiles that list your skills
* Create projects that other people can browse and join
* Secure login via the UH authentication system
* Algorithm suggests relevant projects
* Search for people and projects based on skills


#User Guide

##Landing Page
Logged out users are greeted with information about Alloy and a list of featured projects they can use to get an idea of what interesting things the community is working on. You can log in by selecting the "login" link on the right side of the menu bar.

![](/doc/logged-out-home.png)

##Home Page
When you're logged in, the home page will populate the top menu with your options and switch to displaying suggested projects, which are populated based on the skills you list in the user profile. This is also where you'll see alerts for relevant activity on the site, such as requests to join your project!

![](/doc/logged-in-home.png)

##My Profile
Your profile page is where you can write your bio, show off the projects you're working on, and list your skills! You should make sure to edit your skills via the edit button to make being found and finding projects easier!

![](/doc/user-profile-final.png)

##Create Project
You can create a project by clicking "Create Project" in the menu bar, and filling out the form. The skills are very important, since that's what users will search for, and how your projects will get suggested to other users!

![](/doc/create-project.png)

##Project Page
The project page changes based on your relationship to it, and you can see your options below the project image. For example, if you're logged out, you can only see the title, bio, and featured image, along with a prompt to log in.

![](/doc/logged-out-project.png)

If you're logged in, but aren't a member of the project, you can make a request to join via the button that appears below the featured image.

![](/doc/project-join-request2-final.png)

If you own the project, you get the options to edit the project info, manage members, leave the project, and approve/deny join requests.

![](/doc/profject-profile-final.png)

##Search
When you click to the search page, you'll find the option to search for projects or users. Click one of those two buttons, and then type a skill into the search box, or use the dropdown to browse what skills have been added by users!

![](/doc/search-final.png)      


#Developers Guide
* To begin working on Alloy, meteor must be installed on your machine.
* Create a directory to hold the project
* git clone the project to your machine with
```
git clone https://github.com/alloyteams/alloy.git
```
* From this directory, run
```
meteor npm install
meteor —settings ../config/settings.development.json
```
* Test that Alloy is running on localhost:3000 from any browser

You can then use the editor of your choice to begin modifying Alloy's files. Note that Alloy uses the coding style preferences described [this](http://courses.ics.hawaii.edu/ics314f16/morea/development-environments/ics-se-code-style.xml) xml file.

To get an idea of the project structure, it is helpful to note that Alloy is based on the meteor-application-template available [here](https://ics-software-engineering.github.io/meteor-application-template/)  
