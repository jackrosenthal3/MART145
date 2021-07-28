# MART145

Dear Izzie,

Use this to pull down all the updated files. You should just be able to hit the green "code" button and download the zip. This won't allow you to post back to 
github but it should let you take a copy of the whole updated project. I've included a link at the bottom to the github docs explaing how to copy the repository to 
your local machine using your command terminal as well. I also added some links about installing the dependencies for github on your local machine in case you run 
into any issues downloading it. Also, you can download the github CLI application which will allow you to do less work in your command terminal. Start by just 
trying to download the zip and if that doesn't work try some of the stuff below. Best of luck, have Jack reach out to Alec if you have any problems.

-Jack (Alec)

Github CLI Application download:<br>
https://cli.github.com/

Copy a repository using HTTPS:<br>
https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository

Copy a repository using an SSH key:<br>
Linking SSH key to github:<br>
https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent<br>
Copy repo using SSH key:<br>
https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories<br>

Installing Github locally and its dependencies:<br>
https://docs.gitlab.com/ee/topics/git/how_to_install_git/index.html<br>
https://brew.sh/index.html<br>

If all else fails type the following commands into your command terminal:

xcode-select --install

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install git

git --version
(If the version command doesn't give any errors then git was successfully installed and you should be able to connect remotely)
