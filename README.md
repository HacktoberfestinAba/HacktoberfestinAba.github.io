# HacktoberfestinAba.github.io
This website is hosted on GitHub Pages and the live version can be accessed [here](https://HacktoberfestinAba.github.io).
More about GitHub Pages: https://pages.github.com/

## About
As a means of encouraging participation during Hacktoberfest 2018, this project targets those relatively new to the open source ecosystem and programming in general, but are eager to learn and improve their creative skills by contributing to projects on GitHub.

By creating issues that require easy to complete tasks, we are providing a platform where beginners can readily join the open source movement without being overwhelmed with the restrictions and complexities that plague already established open source projects. We hope that contributors will continue to  confidence as they continue to contribute to this project.

Welcome to the world of Open Source.

## Getting Started
Aiming to be very beginner friendly and to advocate simplicity and clarity, these instructions will get you a copy of this project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
Fork this repository and get started.

### Rules
* Use Pull requests, do not commit to the Master branch or we risk running into conflicting commits.  
* Changes must be confirmed.
* Project maintainers will be in charge of monitoring issues, reviewing submitted patches and merging pull requests. 
* Member contributors will be responsible for collaborating with external contributors to tackle project issues and submit patches via pull requests.
* Please update this readme as needed.

### Prerequisites
To work on this project from your local machine, you would need basic understanding of [Git](https://git-scm.com/) and the [GitHub Workflow](https://guides.github.com/introduction/flow/). Also, experience with web technologies (HTML, CSS, JavaScript) is recommended but not necessary
 a Text Editor/Web IDE, and a recent version of any popular web browser.

### Installing
**Note:** *The dollar sign '$' represents input interface of Mac and Linux machines. Windows users may consider installing Git-Bash.*

On your local machine, navigate to the folder you want to hold your project.
```
$ cd /path-to-folder
```
Clone the forked repository from GitHub.
```
$ git clone https://github.com/<yourusername>/HacktoberfestinAba.github.io
```
Navigate into the cloned repository.
```
$ cd project
```
Create a new branch.
```
$ git branch dev-<yourusername>
```
Switch to your new branch.
```
$ git checkout dev-<yourusername>
```
Make the changes you want on your new branch and when you are done, you can verify the changes using `git status`.

To commit your changes,
first stage the files for commit.
```
$ git add <filename1> <filename2>
```
Verify that the files have been staged.
```
$ git status
```
Then make your commit.
```
$ git commit -m 'commit message'
```
To merge your modifications from the development branch, first switch to the `master` branch.
```
$ git checkout master
```
Merge the development branch with the `master` branch.
```
$ git merge dev-<yourusername>
```
Finally, push your changes to your GitHub repository.
```
$ git push origin master
```

## Deployment

This project doesn't require you running a live server on your local machine. Simply navigate to the project folder and open the `index.html` file to get started.

## Built With

* [HTML, CSS & Javascript](https://) - Web Technologies
* [Git](https://git-scm.com) - Version Control System

## Contributing

Please read [CONTRIBUTING.md](https://github.com/HacktoberfestinAba/HacktoberfestinAba.github.io/CONTRIBUTING.md) for details on our [code of conduct](), and the process for submitting pull requests to us.

## Versioning

We use [Git](https://git-scm.com/) for versioning. For the versions available, see the [tags on this repository](https://github.com/HacktoberfestinAba/HacktoberfestinAba.github.io/tags).

## Author

* David C. Onoh [davidconoh](https://github.com/davidconoh)
* Prosper Opara [0PARA-PROSPER](https://github.com/OPARA-PROSPER)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
* [DigitalOcean](http://digitalocean.com/)
* [GitHub](http://github.com/)
* [Twilio](http://twilio.com/)
