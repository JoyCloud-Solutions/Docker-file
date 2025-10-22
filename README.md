🧭 How I Cloned and Uploaded This Repository to My GitHub



This document outlines the exact steps I followed to clone an existing GitHub repository, edit it locally, and push it to my own GitHub account.



🪄 Step 1: Clone the Repository


I began by cloning the original repository from GitHub to my local computer:


git clone https://github.com/moabukar/tech-vault.git


This created a local copy of the project folder named tech-vault.




📂 Step 2: Navigate Into the Project Directory

I moved into the newly cloned project directory:


cd tech-vault


Then explored its contents using:


ls



🧱 Step 3: Check the Current Remote URL

To see which GitHub repository my local copy was linked to, I ran:

git remote -v


The output showed the project was still linked to the original owner’s repository:


origin  https://github.com/moabukar/tech-vault.git (fetch)
origin  https://github.com/moabukar/tech-vault.git (push)



🧩 Step 4: Create My Own Repository on GitHub

I created a new GitHub repository under my account by visiting

👉 https://github.com/new



I named it TECH-VAULT and copied its new HTTPS link:

https://github.com/JoyCloud-Solutions/TECH-VAULT.git




🔗 Step 5: Update the Remote to My GitHub Repository

I replaced the old remote URL with my new one:


git remote set-url origin https://github.com/JoyCloud-Solutions/TECH-VAULT.git



Then confirmed it with:


git remote -v



Now the output showed:


origin  https://github.com/JoyCloud-Solutions/TECH-VAULT.git (fetch)
origin  https://github.com/JoyCloud-Solutions/TECH-VAULT.git (push)



🚀 Step 6: Push the Repository to My GitHub Account

Finally, I uploaded all local files to my GitHub repository:

git push -u origin main


Git successfully compressed, uploaded, and linked my local main branch to my GitHub repository.



🎉 Step 7: Verify on GitHub

I visited:
👉 https://github.com/JoyCloud-Solutions/TECH-VAULT

and confirmed that all files appeared online — meaning the project was successfully uploaded.


My local project is now fully connected to my GitHub account and ready for future commits and pushes.
