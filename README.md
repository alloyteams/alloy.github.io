##About Alloy
Alloy is a UH student-built tool to help members of the UH iLab and sPACE communities find projects and find people for projects of their own. Have an idea for a project that would look good on your resume? Want to do your own custom senior project? Or do you just want experiment and learn something new with other students who just want to do the same?

Let Alloy help you find a team that's right for what you want.

##Key Features
* Create profiles that list your skills, interests and availability (TODO)
* Create projects that other people can browse and join (TODO)
* Search for people based on skills (TODO)
* Follow people you want to work with to track their projects (TODO)
* Set up alerts for projects that might interest you (TODO)

Alloy is a work in progress, but you can view the current version of the site [here](http://alloytestdeployrv.meteorapp.com/).

[Milestone 1](https://github.com/alloyteams/alloy/projects/1)

[Milestone 2](https://github.com/alloyteams/alloy/projects/2)


#User Guide
##Landing Page
When you first log in, you'll notice that there are several projects featured / suggested to you. Our basic suggestion system is not yet hooked up, but will be ready very soon.

![](/doc/landing-page.png)

##My Profile
On your generated profile page, there are several menu tabs in the top left. Each tab shows different content that are currently just placeholders.

![](/doc/myprofile-page.png)

Scrolling down your profile page, you'll find an unformatted table of dynamically loaded content specific to your profile. You'll notice that you are already a part of a project called "The Null Project." This is a project that all users are automatically entered in and is currently used for debugging purposes.

![](/doc/myprofile-page-table.png)

If you click the associated orange button, you will see a message confirming that you are already a part of the project. Clicking the blue button takes you to the project's home page.

Scrolling down further on the MyProfile page takes you to another table containing a single project called "joinableNullProject." Clicking the orange button here sends a request to admins of the project that you would like to join. Clicking the blue button to get to the joinableNullProject's home page, you will see your request near the bottom of the page. This list will later be private to non-admins of the project, but for now, to get a feel for how the functionality will work, you can click the yellow button to add yourself and other users to the project.

![](/doc/project-request.png)

Navigate back to "TheNullProject" home page through the blue button back on the MyProfile page…

##Project Page
Here on the project profile page, we can see information about the project and, because we are all admins, we can edit this project's profile by clicking the "edit project info" button on the left.

Here we can edit the presented fields and saved changes will be reflected in the project's profile page. Warning, for now, changing the name messes with how Alloy associates users with the projects they are a part of, so avoid changing this for now. Note that in the skills wanted section, skills can be multiple words and each skills is separated by commas (rather than hitting 'enter' after typing each skill).

![](/doc/project-edit.png)

##Create Project
This page can be accessed from the header menu bar. It is similar to the "edit project info" functionality, except here we can create new projects rather than edit existing info. Note that although the "Skills Wanted" section provides a list of suggested skills, like in the "edit project info" page, you can enter any phrase that does not contain a comma. Any new skills and phrases you enter will be saved and possibly suggested in the "Skills Wanted" dropdown menu the next time a user creates a project.

##Search
This page can be accessed from the header menu bar. This page can be used to search for projects and users based on skills wanted and skills available, respectively. Currently, the search terms must be exact word matches and the search results must be cleared each time with the "clear" button. 

![](/doc/search-projects.png)      


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

#Screenshots
##Public Landing Page
![landing page](/doc/landing-page.png)
##Add Project
![user home page](/doc/AlloyM1AddProject.png)
##Edit Project
![user profile](/doc/AlloyM1EditProject.png)




