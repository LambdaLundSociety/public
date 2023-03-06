# GitHub instructions

In this guide I will guide you through the steps that has to be taken to upload your code and get access to the code uploaded by other Lambda members ~ Janek

Text to Janek, Johannes or Keshav with jour GitHub nickname to be added to the `LambdaLundSociety` organization on Git. You will find your nickname in the right upper corner:

![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled.png)

When you’ll get access to the organization you will see this view with access to private repositories inside the organization. Otherwise you can see only public repositories, but we don’t have right now

![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled%201.png)

### Creating new private repository inside the organization

Now we can create our own repository:

1. Click **New repository** button and fill out the template in this way:
    
    ![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled%202.png)
    

Now you’re in the initial view of your own repository. Everyone can get access to it in the same away as below. Click **<> Code** and ****copy button next to HTTPS link: 

![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled%203.png)

Now open **Terminal**  and with `cd`  command change directory to the folder where you want to keep your files. You can start typing name of following folders and using **Tab** it will be autocompleted. 

![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled%204.png)

This is how my folder tree looks like to give you better understanding

![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled%205.png)

Now enter `git clone` command with adding HTTPS link of the repository you want to clone after. 

![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled%206.png)

Now, you will be asked for your login and then password. But since 2021 GitHub doesn’t allow for authentication password, so you have to use **Personal tokens** that you can generate in the settings as explained below.

**Generating token for authentication:**

Enter this link to the right page in settings: https://github.com/settings/tokens  

Click **********************************************************Generate new token (classic):********************************************************** 

![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled%207.png)

Now, fill the tag name to identify the token, set expiration time period and fill repo checkbox as probably you will only use this functionality:

![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled%208.png)

After confirming the settings you will see your long personal token and keep it in some safe space, it’s the last time you see this token so save it in a safe space. 

Alright! Now enter your username and then the token and press Enter!

Now, this is how your terminal will look like:

![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled%209.png)

And now you will see the repository itself on your computer, my is called `beautiful_monday`:

![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled%2010.png)

But it’s a little empty here 😕 Okay, so let’s upload some files there!

I copied two files into the repository. While doing a project of course this folder will be your main repository and you can easily update or upload new files with following commands:

1. `git add .` - this will add all files with their updates 
2. `git diff —cached` - you can see what changes will you execute in git repository. Green coloured are new lines, red coloured are deleted ones, etc. everything clearly explained. You can explore all the changes with clicking **Enter** or just click **Q** if you’re done with checking these changes. 

![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled%2011.png)

1. `git commit -m "I uploaded an easter egg with python rules :-)"` -this comment will be shown with changes you made to the repository.
2. `git push origin main` - with this command all the changes will be pushed to the main branch

![Untitled](GitHub%20instructions%20736af4d4964c43b08b132159fbc04f26/Untitled%2012.png)

Now, these files are available in the repository 😀