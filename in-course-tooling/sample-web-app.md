---
description: >-
  This exercise is required for the hands-on in the Backend workshop (11th Nov,
  Mon)
---

# 📲 Building a Sample Web App

### 1. Create a new GitHub Repository

* Go to [https://github.com/new](https://github.com/new) to create a new repository
* Type in your own repository name (this could be any name)
* The description for your repository can be empty
* Your repository should by default be Public
* Ensure that you check the "**Add a README file**"
* Ensure that you select **Node** as the .gitignore template
* The license can be at it's default setting of None
* Note that your default branch may be called "master" or "main", this is okay and you can leave it (mine is currently set as "develop").
* Click on "Create repository" to create your new GitHub Repository

<figure><img src="../.gitbook/assets/sample-2.avif" alt=""><figcaption><p>A sample of the options selected before clicking "Create repository"</p></figcaption></figure>

### 2. Open your newly created repository in Codespaces

* You should have been re-directed to your newly created repository
* Click on the green "Code" button, select the "Codespaces" tab and click **"Create Codespace on develop"**. (Note: your branch may be called "master" or "main" and this is fine)

<figure><img src="../.gitbook/assets/sample-3.avif" alt=""><figcaption><p>Click on create codespace to open up codespaces for your repository</p></figcaption></figure>

### 3. Download the source code and unzip the file

* Your GitHub Codespace should have opened up in a new tab after creating a codespace in the previous step.

#### Click on the link below to download the source code for the sample app here and unzip the file:



{% file src="../.gitbook/assets/techup-sample-blog-9apr.zip" %}

<figure><img src="../.gitbook/assets/sample-4.avif" alt=""><figcaption><p>You should see the following files and folders after unzipping the zip file</p></figcaption></figure>

### 4. Drag and drop sample app code into Codespaces

* After completing Step 2, a new tab should have opened with your Codespace similar to the image shown below.

<figure><img src="../.gitbook/assets/sample-5.avif" alt=""><figcaption><p>Your Codespace for your newly created GitHub repository</p></figcaption></figure>

* Drag and drop all files and folders in Step 3 into the sidebar of your Codespace. IMPORTANT: Ensure that you select all the files and folders INSIDE the unzipped file, do not upload the whole zip file (see the below images if you are unsure).

<figure><img src="../.gitbook/assets/sample-6.avif" alt=""><figcaption><p>Select all the files and folders INSIDE the unzipped file to upload to Codespace</p></figcaption></figure>



<figure><img src="../.gitbook/assets/sample-7.avif" alt=""><figcaption><p>Drop the selected folders and files in the section marked by the red box</p></figcaption></figure>

<figure><img src="../.gitbook/assets/sample-8.gif" alt=""><figcaption><p>Ensure you drag and drop the correct files in the right location</p></figcaption></figure>

* This uploads the sample web app source code to your Codespace
* After dragging and dropping, your Codespace should look like this with the following files in the sidebar

<figure><img src="../.gitbook/assets/sample-9.avif" alt=""><figcaption><p>Note the newly added folders of "prisma", "public", "views" and files "package-lock.json", "package.json", "server.js"</p></figcaption></figure>

### 5. Commit & Push to your repository

* Click on the Source Control icon (the icon which has blue numbers on it, in the image above it's the third tab on the left)
* Enter a commit message of "Uploaded sample code"
* Click on the dropdown next to "Commit" and click on "Commit & Push".
* Note that you will have to click on the drop down arrow for "Commit & Push" to show up

<figure><img src="../.gitbook/assets/sample-10b.png" alt=""><figcaption><p>Click on the Source Control tab, write a commit message and click on "Commit &#x26; Push" from the drop down list</p></figcaption></figure>

* If the following pop-up appears, select "Always"

<figure><img src="../.gitbook/assets/sample-11.avif" alt=""><figcaption><p>Select "Always" should this pop-up appear after clicking "Commit &#x26; Push"</p></figcaption></figure>

* Another pop up may appear at the bottom right of your screen, select the option of "Yes"

<figure><img src="../.gitbook/assets/sample-12.avif" alt=""><figcaption><p>Select "Yes" should this pop-up appear on the bottom right of your screen</p></figcaption></figure>

* Check that your files are in your GitHub repository by going to https://github.com and selecting the repository you created in Step 1

<figure><img src="../.gitbook/assets/sample-13.avif" alt=""><figcaption><p>Select your repository in the sidebar on the left</p></figcaption></figure>

* You should now see that there are the newly uploaded files in this repository

<figure><img src="../.gitbook/assets/sample-14.avif" alt=""><figcaption><p>The files should now be in your repository you created</p></figcaption></figure>

### 6. Create a new PostgreSQL database on Render

* Go to [https://dashboard.render.com/new/database](https://dashboard.render.com/new/database) to create a new PostgreSQL database on Render.
* Type in a Name for your PostgreSQL instance (I've named mine techup-sample-database)
* Leave the Database field blank
* Leave the User field blank
* Change the Region to "Singapore (Southeast Asia)
* Leave PostgreSQL Version as the default value of 16
* Leave the Datadog API Key field blank
* Change your instance type to FREE
* Click on "Create Database"

<figure><img src="../.gitbook/assets/sample-15.avif" alt=""><figcaption><p>Enter a Name for your instance and change the Region to Singapore while leaving other fields as their default values</p></figcaption></figure>

<figure><img src="../.gitbook/assets/sample-16.avif" alt=""><figcaption><p>Change your Instance Type to FREE before clicking on Create Database</p></figcaption></figure>

{% hint style="info" %}
Note that, at this step, you may be asked to enter your **credit card details** to verify your identity; without which, you cannot proceed.&#x20;

We would recommend that you proceed to do so. For the programme, you should not be incurring any expenses from the use of Render, as we will be using the **free plan** by default. That said, should you be using a paid plan for improved functionality, you should also be able to claim for reimbursement, as each participant has been [allocated a $100 budget](../pre-work/tooling-and-software/tooling-claims-instructions.md) for tooling purposes.&#x20;
{% endhint %}

* Your database should now be created (after about 30 seconds)
* Scroll down to the section on Connections and take note of the `External Database URL`
* Copy this `External Database URL` to a blank word document (or anywhere else such as Notepad) as you will be using it later to add it as an environment variable.
* **IMPORTANT: PLS ENSURE YOU HAVE COPIED THIS URL AS YOU NEED IT LATER.**

<figure><img src="../.gitbook/assets/sample-17.avif" alt=""><figcaption><p>Click on "Copy to clipboard" for the External Database URL to copy this URL for use later</p></figcaption></figure>

### 7. Create a new Web Service on Render

* Go to [https://dashboard.render.com/create?type=web](https://dashboard.render.com/create?type=web) to create a new Web Service (alternatively you may also click on the purple New + button at the top of the page and select Web Service)
* Ensure "Build and deploy from a Git repository" is selected then click Next

<figure><img src="../.gitbook/assets/sample-18.avif" alt=""><figcaption><p>Ensure the first option of "Build and deploy from a Git repository" is selected</p></figcaption></figure>

* On the right column you will need to click on "+ Connect Account" to connect your GitHub account to Render.
* Click on "Connect" for the repository name which your created in Step 1

<figure><img src="../.gitbook/assets/sample-19.avif" alt=""><figcaption><p>Click Connect on the repository created in Step 1 (if this dropdown list is not showing you will need to click on + Connect Account on the page to connect your GitHub account to Render)</p></figcaption></figure>

* Leave the Name field as it's default value
* Ensure that the Region is set to "Singapore (Southeast Asia)"
* Ensure that your Branch is selected (yours may be called "master" or "main")
* Leave the Root Directory field blank
* Leave the Runtime as "Node"
* Change the Build Command to `yarn; npx prisma db push; npx prisma generate`

<figure><img src="../.gitbook/assets/sample-20.avif" alt=""><figcaption><p>Change the Build Command to as shown above</p></figcaption></figure>

* Add the Start Command of `node server.js`
* Change the Instance Type to FREE

<figure><img src="../.gitbook/assets/sample-21.avif" alt=""><figcaption><p>Add the Start Command to "node server.js" and change the Instance Type to FREE</p></figcaption></figure>

* Add a new Environment Variable of name `DATABASE_URL` with the value of your copied `External Database URL` in Step 6. _(If you have misplaced this URL, not to worry. Go to_ [_https://dashboard.render.com/_](https://dashboard.render.com/) _and click on your database. Scroll down and simply copy the External Database URL again.)_

<figure><img src="../.gitbook/assets/sample-22.avif" alt=""><figcaption><p>Create a new Environment Variable of "DATABASE_URL" and paste the External Database URL copied earlier as its value</p></figcaption></figure>

* Click on the "Create Web Service" button to start deploying
* You will be redirected to a new page which shows the logs of the server build happening. It would take approximately 2-4mins for the the server to full deploy your app.
* Your app is deployed once you see the line "==> Your service is live 🎉" in the logs.

<figure><img src="../.gitbook/assets/sample-23.avif" alt=""><figcaption><p>Your app is ready once you see "Your service is live 🎉"</p></figcaption></figure>

### 8. Accessing your newly deployed web application

* At the top of the same deploy page with the logs, you will see a URL (in my case it is [https://techup-blog.onrender.com](https://techup-blog.onrender.com/)). Click on this link and it will bring you to your web application.

<figure><img src="../.gitbook/assets/sample-24.avif" alt=""><figcaption><p>Click on the URL at the top left to bring you to your newly deployed web app</p></figcaption></figure>

* You should now be able to view the sample web app which you have deployed on your own Render server!

<figure><img src="../.gitbook/assets/sample-25.avif" alt=""><figcaption><p>Congrats!! You have successfully deployed the sample web app on your own Render server</p></figcaption></figure>

* Have fun playing around with the sample web app by Adding and Deleting blog posts!

## Optional: How do I view what is inside my Postgres database which I created on Render.com?

#### 1. Download and install TablePlus from [https://tableplus.com/](https://tableplus.com/)

<figure><img src="../.gitbook/assets/sample-26.avif" alt=""><figcaption><p>Dowload TablePlus for Mac or TablePlus for Windows depending on what laptop you have</p></figcaption></figure>

#### 2. Open TablePlus and click on the + icon to add a new connection

<figure><img src="../.gitbook/assets/sample-27.avif" alt=""><figcaption><p>Click on the + icon to add a new connection</p></figcaption></figure>

#### 3. Click on Import from URL

<figure><img src="../.gitbook/assets/sample-28.avif" alt=""><figcaption><p>Click on Import from URL</p></figcaption></figure>

#### 4. Paste the `External Database URL` (which you copied earlier when setting up Postgres) into the text field then click Import



<figure><img src="../.gitbook/assets/sample-29.avif" alt=""><figcaption><p>Paste your External URL into the field then click Import</p></figcaption></figure>

#### 5. Click on Connect (you may rename the "Name" field or leave it as it's default)

<figure><img src="../.gitbook/assets/sample-30.avif" alt=""><figcaption><p>Click on connect</p></figcaption></figure>

#### 6. You have now successfully connected to the database from TablePlus and you may click on the Post table in the left sidebar to view the contents

<figure><img src="../.gitbook/assets/sample-31.avif" alt=""><figcaption><p>Success! You can click on the Post table to view the contents</p></figcaption></figure>
