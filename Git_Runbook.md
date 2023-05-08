<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> GIT RUNBOOK </p>

# <div align="center"> DevOps Instructor-led Training </div>

<br />

<br />

<br />

<br />

# $${\color{brown} &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; Contact us: &emsp;&emsp;&emsp; }$$

<div align="right"> T O A C C E L E R A T E Y O U R C A R E E R G R O W T H </div>

### <div align="right"> For questions and more details: </div>

<div align="right"> <img src=https://w7.pngwing.com/pngs/759/922/png-transparent-telephone-logo-iphone-telephone-call-smartphone-phone-electronics-text-trademark-thumbnail.png width="20" height="20"> +91 98712 72900 </div>

<div align="right"> <img src=https://pbs.twimg.com/profile_images/1450734615946219520/jmBHQRRa_400x400.jpg width="20" height="20"> https://www.thecloudtrain.com </div>

<div align="right"> <img src=https://icons.iconarchive.com/icons/martz90/circle/512/email-icon.png width="20" height="20"> support@thecloudtrain.com </div>

<div align="right"> <img src=https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-whatsapp-icon-png-image_6315990.png width="20" height="20"> +91 98712 72900 </div>

## _Find solutions to your assingment below:_

### Exercise 1: Complete below tasks as part of this exercise:

A) Setup a GitHub account and create one repository inside it named 'devopsdemo'

### _Solution:_

i. Open https://github.com/ in browser and click on signup:

![](RackMultipart20230508-1-iwyavi_html_c4e69d82722015bb.png)

ii. Fill the form by choosing one username, entering email and password for the Github account. Solve the puzzle to verify the account

![](RackMultipart20230508-1-iwyavi_html_8a38da1b3e0de9ca.png)

iii. Once all done, click on create account
iv. You must receive email from Github for account verification with verification link. Complete the verification to complete registration process.
v. Once registration is complete, login to the Github account and generate Personal Access Token next:

**Generate Personal Access Token for authentication(Step vi to xiii):**

vi. In the upper-right corner of any page, click your profile photo, then click  **Settings**.

![Picture 1](RackMultipart20230508-1-iwyavi_html_ac1044079ba43f2b.gif)

vii. In the left sidebar, click  **Developer settings**.

![Picture 2](RackMultipart20230508-1-iwyavi_html_737539572c93785d.gif)

viii. In the left sidebar, click  **Personal access tokens**. ![Picture 3](RackMultipart20230508-1-iwyavi_html_1a0fa839d2add4f8.gif)
ix. Click  **Generate new token**. ![](RackMultipart20230508-1-iwyavi_html_507bdc0a6e555560.png)
x. Give your token a descriptive name. ![](RackMultipart20230508-1-iwyavi_html_f0db5b759f3b6697.png)
xi. To give your token an expiration, select the  **Expiration**  drop-down menu, then click a default or use the calendar picker. ![](RackMultipart20230508-1-iwyavi_html_c484f6055090c0a8.png)
xii. Select the scopes, or permissions, you'd like to grant this token. To use your token to access repositories from the command line, select  **repo**.

![](RackMultipart20230508-1-iwyavi_html_40c5e6ec14916e24.png)

xiii. Click  **Generate token**. ![](RackMultipart20230508-1-iwyavi_html_aa72ea36c653f7c5.png)

![Picture 9](RackMultipart20230508-1-iwyavi_html_28074feb005a14f5.gif)

_**Warning** :  **Copy the token generated** and save it somewhere. Treat your tokens like passwords and keep them secret. When working with the API, use tokens as environment variables instead of hardcoding them into your programs._

### Example of using your access token instead of password, because password authentication is deprecated:

```
git push origin master

Username: <your_username>
Password: <your_token>
```

xiv. Create repository now by clicking on 'New repository':

![](RackMultipart20230508-1-iwyavi_html_8a82e30422835d3b.png)

xv. Fill the repo name as **devopsdemo** and click create repo as below:

![](RackMultipart20230508-1-iwyavi_html_e6d0102f61b97daf.png)

xvi. Once repo is created, you will see page like below:

![](RackMultipart20230508-1-iwyavi_html_2be76b6d71ffd626.png)

xvii. Copy the repo clone URL under code and go to **task b**.

B) Clone this repo 'devopsdemo' to your GCP compute instance

### _Solution:_

Login to your Ubuntu GCP instance with ubuntu user and run below command to clone:

`sudo su – ubuntu`

`git clone https://github.com/vistasunil/devopsdemo.git`

![](RackMultipart20230508-1-iwyavi_html_4712f9a8b79a6ad0.png)

C) cd to the repo directory you just cloned

### _Solution:_

`cd devopsdemo`

![](RackMultipart20230508-1-iwyavi_html_b725201849f00a09.png)

D) Check the branch name you are checked out currently. It should be **master** by default.

### _Solution:_

`git branch`

![](RackMultipart20230508-1-iwyavi_html_42b753f3f1fb2353.png)

E). Add two files using vim editor as below:
  1. File1.txt
  2. File2.txt

### _Solution:_

`vim File1.txt`

`vim File2.txt`

![](RackMultipart20230508-1-iwyavi_html_97016980fc1382fd.png)

F) Check the git status

### _Solution:_

`git status`

![image](https://user-images.githubusercontent.com/37858762/236855760-644c6d6b-1311-4e2f-a914-dbec3e022c93.png)

G) Add and Commit the changes to the repo

### _Solution:_

`git add .`

![image](https://user-images.githubusercontent.com/37858762/236855711-21ef3c3a-c4aa-4b6c-a5ac-8a469b1c1db8.png)

`git commit -m 'My first commit'`

![image](https://user-images.githubusercontent.com/37858762/236855677-7e72d46d-6204-4cc7-818e-551fa9dc0a60.png)

H) Push the changes to the repo 'devopsdemo' to github account

### _Solution:_

`git push`

![image](https://user-images.githubusercontent.com/37858762/236855627-d9abd8ad-3208-46b1-84aa-704bd81a5dfe.png)

You will see files successfully pushed to Github account in the devopsdemo repo as below:

![image](https://user-images.githubusercontent.com/37858762/236855612-817282f1-6b1f-4cfd-b3c4-4008db6f0172.png)

### Exercise 2: Complete below tasks as part of this exercise:

A) cd to the repo directory 'devopsdemo' on the server

### _Solution:_

`cd devopsdemo`

![image](https://user-images.githubusercontent.com/37858762/236855581-6f0c16b4-da49-4193-a0b9-42ba4b6d7800.png)

B) create a new branch with name **feature1**

### _Solution:_

`git branch feature1`

![image](https://user-images.githubusercontent.com/37858762/236855541-f541c60e-1d02-4c68-9437-f2e055deac6b.png)

C) Checkout to feature1 branch

### _Solution:_

`git checkout feature1`

![image](https://user-images.githubusercontent.com/37858762/236855499-5bc96802-330b-4e63-81dd-e4b6a14da98d.png)

D) Add two files using vim editor as below:
  1. File3.txt
  2. File4.txt

### _Solution:_

`vim File1.txt`

`vim File2.txt`

![image](https://user-images.githubusercontent.com/37858762/236855469-3386cc27-8c26-4275-b255-ac2a5ab6055b.png)

![image](https://user-images.githubusercontent.com/37858762/236855421-3016eff5-5a21-4f90-9dab-0f34d0800d2e.png)

You see four files now in **feature1** branch

![image](https://user-images.githubusercontent.com/37858762/236855368-d6d1e39d-59ed-4a52-88d3-e57aefbcf7d3.png)

E) Check status, add files, commit and push to github account

### _Solution:_

`git add .`

![image](https://user-images.githubusercontent.com/37858762/236855338-5d593e3e-540c-4240-b922-2aef16f3a8e9.png)

`git commit -m 'My feature1 commit'`

![image](https://user-images.githubusercontent.com/37858762/236855301-f97578bd-518e-4293-8de8-e754ad319533.png)

F) Merge the changes in **feature1** branch to master branch

### _Solution:_

![image](https://user-images.githubusercontent.com/37858762/236855220-6cb494d7-bd55-461b-8493-5f66344d706e.png)

![](RackMultipart20230508-1-iwyavi_html_9ec02f07f5b65337.png)

Before git merge you will see only old two files in main branch as below:

![image](https://user-images.githubusercontent.com/37858762/236855191-bdead230-ce8e-4db4-876c-177042888f12.png)

Now merge feature1 to main branch

`git merge feature1`

![image](https://user-images.githubusercontent.com/37858762/236855156-92376691-c18b-41ee-95c5-b6731cc1a713.png)

G) Check if all changes from **feature1** branch are available under master branch after merge.

### _Solution:_

After merge you will all files available from feature1 branch in main branch too.

`ls -ltr`

![image](https://user-images.githubusercontent.com/37858762/236855125-fdc7883d-f30c-4339-887f-ff6bfb1953b8.png)
