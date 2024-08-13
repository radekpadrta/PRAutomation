## What is needed to have preview environments?

Static web is needed
 - You need linked your Static web app with Repo code, in our case with GitHub.
 - You select organization (my account)
 - Repository (where is code located)
 - Branch (in Azure you can select only one branch, but in GitHub Action you can put it more branches)
 
 ![](https://github.com/radekpadrta/PRAutomation/blob/226a4d524dc922c1cd752a6782f753711d3d3b55/Pasted%20image%2020240812155658.png)

When you create Static Web App with your code you will have production environment = this is the code what you have.

## How to create Preview Environment?

When you link Static Web App with Github, the GitHub Action is created automatically.

![](https://github.com/radekpadrta/PRAutomation/blob/226a4d524dc922c1cd752a6782f753711d3d3b55/Pasted%20image%2020240812160208.png)
In this code, we can see it is waiting if we create a PR. If we create a PR or push/close, the build will be triggered and it creates a preview Environment.

We can see it here (don't look at the first build, it was just my mistake :). But in the second build, we can see the GitHub action was created.

![](https://github.com/radekpadrta/PRAutomation/blob/226a4d524dc922c1cd752a6782f753711d3d3b55/Pasted%20image%2020240812160442.png)

## What can we see in Azure?

We can see the actual PR name in Preview Environments - You can check the picture above for the name of the PR.

![](https://github.com/radekpadrta/PRAutomation/blob/226a4d524dc922c1cd752a6782f753711d3d3b55/Pasted%20image%2020240812160617.png)

## Thoughts 

I didn't get any URL link in PR comments.. probably needs to be written in GitHub action, which is not defined automatically.

You can work with one code, you need to update Github Action if you want to select which code you want. But there is no option how to select the code from a user perspective. Still there will be some action to upgrade the GitHub action.

It is good, if you push changes to your repo and you have a PR open, the Github Action automatically pushes changes to preview Environment = no need to remove environment and build again.


aaaa
