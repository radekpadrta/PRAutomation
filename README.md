## What is needed to have preview environments?

Static web is needed
 - You need linked your Static web app with Repo code, in our case with GitHub.
 - You select organization (my account)
 - Repository (where is code located)
 - Branch (in Azure you can select only one branch, but in GitHub Action you can put it more branches)![[Pasted image 20240812155658.png]]

When you create Static Web App with your code you will have production environment = this is the code what you have.

## How to create Preview Environment?

When you linked Static Web App with Github, the GitHub Action was created automatically.

![[Pasted image 20240812160208.png]]
In this code, we can see, it is waiting if we create PR. If we create PR or push/closed the build will be triggered and it creates preview Environment.

We can see it here (don't look for first build, it was just my mistake :). But in the second build we can see the GitHub action was created.

![[Pasted image 20240812160442.png]]

What can we see in Azure?

We can see the actual PR name in Preview Environments  - You can check picture above the name of the PR.

![](/Pasted image 20240812160617.png)

### Negative thoughts 

I didn't get any URL link in PR comments.. probably need to be written in GitHub action, which is not define automatically.

You can work with one code, you need to update Github Action if you want to select which code you want. But there is no option how to select the code from user perspective.




#### LINKS:




12-08-2024-15:48

---

[[]]