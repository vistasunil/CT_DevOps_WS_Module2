<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> GIT RUNBOOK </p>

# <div align="center"> DevOps Workshop Training </div>

# <div align="right"> $`\textcolor{brown}{\text{Contact us: }}`$  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; </div>

<div align="right"> T O A C C E L E R A T E Y O U R C A R E E R G R O W T H </div>

### <div align="right"> For questions and more details: </div>

<div align="right"> <img src=https://w7.pngwing.com/pngs/759/922/png-transparent-telephone-logo-iphone-telephone-call-smartphone-phone-electronics-text-trademark-thumbnail.png width="20" height="20"> +91 98712 72900 </div>

<div align="right"> <img src=https://pbs.twimg.com/profile_images/1450734615946219520/jmBHQRRa_400x400.jpg width="20" height="20"> https://www.thecloudtrain.com </div>

<div align="right"> <img src=https://icons.iconarchive.com/icons/martz90/circle/512/email-icon.png width="20" height="20"> support@thecloudtrain.com </div>

<div align="right"> <img src=https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-whatsapp-icon-png-image_6315990.png width="20" height="20"> +91 98712 72900 </div>

#
</br>

## $`\textcolor{red}{\text{NOTE: USE UBUNTU 22.04 VIRTUAL MACHINES FOR ALL THE LABS}}`$

## _Find solutions to Git assingment below:_

### Exercise 1: Complete below tasks as part of this exercise:

a) Setup a GitHub account and create one repository inside it named 'devopsdemo'

### _Solution:_

i. Open https://github.com/ in browser and click on signup:

![image](https://user-images.githubusercontent.com/37858762/236856920-69b5b091-8803-4f1b-a513-2ba7632f8eb8.png)

ii. Fill the form by choosing one username, entering email and password for the Github account. Solve the puzzle to verify the account

![image](https://user-images.githubusercontent.com/37858762/236856881-fc24767a-5ef0-4aeb-bb71-a2102ce2b485.png)

iii. Once all done, click on create account
iv. You must receive email from Github for account verification with verification link. Complete the verification to complete registration process.
v. Once registration is complete, login to the Github account and generate Personal Access Token next:

**Generate Personal Access Token for authentication(Step vi to xiii):**

vi. In the upper-right corner of any page, click your profile photo, then click  **Settings**.

![image](https://user-images.githubusercontent.com/37858762/236856840-51da035f-1565-4b7c-8581-19cc4b8b25f4.png)

vii. In the left sidebar, click  **Developer settings**.

![image](https://user-images.githubusercontent.com/37858762/236856813-7482cff7-f481-42d7-8a6d-ac95db286f63.png)

viii. In the left sidebar, click  **Personal access tokens**. 

![image](https://user-images.githubusercontent.com/37858762/236856762-bdd4e233-e263-48b9-995d-f71fe19f2f72.png)

ix. Click  **Generate new token**. 

![image](https://user-images.githubusercontent.com/37858762/236856728-456de00b-949f-47a3-a552-fd32f6ec41a7.png)

x. Give your token a descriptive name. 

![image](https://user-images.githubusercontent.com/37858762/236856682-f4b78aab-3686-4fe4-87ea-b966bc8cbd3c.png)

xi. To give your token an expiration, select the  **Expiration**  drop-down menu, then click a default or use the calendar picker. 

![image](https://user-images.githubusercontent.com/37858762/236856618-89e05fa0-0a96-48cc-bcbf-868c79c4b8c8.png)

xii. Select the scopes, or permissions, you'd like to grant this token. To use your token to access repositories from the command line, select  **repo**.

![image](https://user-images.githubusercontent.com/37858762/236856575-7b536517-e9a5-41b6-a6cb-340fab9fe1ee.png)

xiii. Click  **Generate token**. 

![image](https://user-images.githubusercontent.com/37858762/236856526-015ae176-1528-4b97-adf6-13ea2f97dc59.png)

![image](https://user-images.githubusercontent.com/37858762/236856499-ac95058d-56fc-485f-a160-175f7e5704ac.png)

_**Warning** :  **Copy the token generated** and save it somewhere. Treat your tokens like passwords and keep them secret. When working with the API, use tokens as environment variables instead of hardcoding them into your programs._

**Example of using your access token instead of password, because password authentication is deprecated:**

```
git push origin master

Username: <your_username>
Password: <your_token>
```

xiv. Create repository now by clicking on 'New repository':

![image](https://user-images.githubusercontent.com/37858762/236856439-e833cbe5-cad7-436f-8519-c6a0249cc281.png)

xv. Fill the repo name as **devopsdemo** and click create repo as below:

![image](https://user-images.githubusercontent.com/37858762/236856403-5e938f74-9482-4abf-8315-9ccb30340532.png)

xvi. Once repo is created, you will see page like below:

![image](https://user-images.githubusercontent.com/37858762/236856323-2df61357-2602-401b-abb4-18ca4fc11e34.png)

xvii. Copy the repo clone URL under code and go to **task B**.

b) Clone this repo 'devopsdemo' to your GCP compute instance

### _Solution:_

Login to your Ubuntu GCP instance with ubuntu user and run below command to clone:

`sudo su – ubuntu`

`git clone https://github.com/vistasunil/devopsdemo.git`

![image](https://user-images.githubusercontent.com/37858762/236856262-b181173c-45dc-4e5b-91fb-fd4ef7709171.png)

c) cd to the repo directory you just cloned

### _Solution:_

`cd devopsdemo`

![image](https://user-images.githubusercontent.com/37858762/236856219-e3a23d9b-ac68-41fe-8c80-00d53e821176.png)

d) Check the branch name you are checked out currently. It should be **master** by default.

### _Solution:_

`git branch`

![image](https://user-images.githubusercontent.com/37858762/236856187-a7f1277b-d548-4d0a-a59f-3cf21751aa5f.png)

e). Add two files using vim editor as below:
  1. File1.txt
  2. File2.txt

### _Solution:_

`vim File1.txt`

`vim File2.txt`

![image](https://user-images.githubusercontent.com/37858762/236856150-fe3c3266-38a9-47c9-b272-4e0576ae63c3.png)

f) Check the git status

### _Solution:_

`git status`

![image](https://user-images.githubusercontent.com/37858762/236856113-d091db23-31cd-4fc4-9795-3a8d474d1789.png)

g) Add and Commit the changes to the repo

### _Solution:_

`git add .`

![image](https://user-images.githubusercontent.com/37858762/236856090-9c8c03c2-773a-4c51-845f-7da357999f8f.png)

`git commit -m 'My first commit'`

![image](https://user-images.githubusercontent.com/37858762/236855677-7e72d46d-6204-4cc7-818e-551fa9dc0a60.png)

h) Push the changes to the repo 'devopsdemo' to github account

### _Solution:_

`git push`

![image](https://user-images.githubusercontent.com/37858762/236855627-d9abd8ad-3208-46b1-84aa-704bd81a5dfe.png)

You will see files successfully pushed to Github account in the devopsdemo repo as below:

![image](https://user-images.githubusercontent.com/37858762/236855612-817282f1-6b1f-4cfd-b3c4-4008db6f0172.png)

### Exercise 2: Complete below tasks as part of this exercise:

a) cd to the repo directory 'devopsdemo' on the server

### _Solution:_

`cd devopsdemo`

![image](https://user-images.githubusercontent.com/37858762/236855581-6f0c16b4-da49-4193-a0b9-42ba4b6d7800.png)

b) create a new branch with name **feature1**

### _Solution:_

`git branch feature1`

![image](https://user-images.githubusercontent.com/37858762/236855541-f541c60e-1d02-4c68-9437-f2e055deac6b.png)

c) Checkout to feature1 branch

### _Solution:_

`git checkout feature1`

![image](https://user-images.githubusercontent.com/37858762/236855499-5bc96802-330b-4e63-81dd-e4b6a14da98d.png)

d) Add two files using vim editor as below:
  1. File3.txt
  2. File4.txt

### _Solution:_

`vim File1.txt`

`vim File2.txt`

![image](https://user-images.githubusercontent.com/37858762/236855469-3386cc27-8c26-4275-b255-ac2a5ab6055b.png)

![image](https://user-images.githubusercontent.com/37858762/236855421-3016eff5-5a21-4f90-9dab-0f34d0800d2e.png)

You see four files now in **feature1** branch

![image](https://user-images.githubusercontent.com/37858762/236855368-d6d1e39d-59ed-4a52-88d3-e57aefbcf7d3.png)

e) Check status, add files, commit and push to github account

### _Solution:_

`git add .`

![image](https://user-images.githubusercontent.com/37858762/236855338-5d593e3e-540c-4240-b922-2aef16f3a8e9.png)

`git commit -m 'My feature1 commit'`

![image](https://user-images.githubusercontent.com/37858762/236855301-f97578bd-518e-4293-8de8-e754ad319533.png)

f) Merge the changes in **feature1** branch to master branch

### _Solution:_

![image](https://user-images.githubusercontent.com/37858762/236855220-6cb494d7-bd55-461b-8493-5f66344d706e.png)

![](RackMultipart20230508-1-iwyavi_html_9ec02f07f5b65337.png)

Before git merge you will see only old two files in main branch as below:

![image](https://user-images.githubusercontent.com/37858762/236855191-bdead230-ce8e-4db4-876c-177042888f12.png)

Now merge feature1 to main branch

`git merge feature1`

![image](https://user-images.githubusercontent.com/37858762/236855156-92376691-c18b-41ee-95c5-b6731cc1a713.png)

g) Check if all changes from **feature1** branch are available under master branch after merge.

### _Solution:_

After merge you will all files available from feature1 branch in main branch too.

`ls -ltr`

![image](https://user-images.githubusercontent.com/37858762/236855125-fdc7883d-f30c-4339-887f-ff6bfb1953b8.png)
