pipelette8761.github.io
# How to Host a Resume on GitHub Pages

### Purpose :
The following will describe in detail how I formatted and hosted my resume on GitHub Pages using Markdown, a Markdown editor known as Atom, and a static site generator called Jekyll. In addition, I will relate each step of the process to Andrew Etter’s book *Modern Technical Writing*, which discusses the general principles of current Technical Writing.  

### Prerequisites :
1. Basic knowledge of Markdown. Refer to More Resources in this doc for a link to a Markdown tutorial.
2. A GitHub account. Refer to More Resources in this doc for a link from GitHub on how to get started.
3. A resume formatted in Markdown.
4. Some coffee or tea for moments where you have no idea what you're doing.

### Instructions :
#### Creating a GitHub account
*skip this step if you already have one*  
  
1. Under More Resources in this doc, click the link for Getting started with GitHub.
2. Do the steps outlined in *Part 1: Configuring your GitHub account* on the page that opened.

#### Setting up Git and connecting over SSH
*skip this step if you don't plan to work with files locally*

1. Head over to https://docs.github.com/en/get-started/quickstart/set-up-git.
2. Under *Next steps: Authenticating with GitHub from Git -> Connecting over SSH*, click generate SSH keys.(https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
3. Choose your operating system (Mac, Windows or Linux) on the page that opened.
4. Follow and complete each step. For step 7 of *Generating a new SSH key for a hardware security key*, click *Adding a new SSH key to your GitHub account*.  
(https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
6. Choose your operating system (Mac, Windows or Linux) on the page that opened.
7. Choose Web browser instead of GitHub CLI if the latter's showing.
8. Follow and complete each step.

Congrats ! If you got this far, you now have Git set up locally and will be able to use Git on the command line.

#### Creating a GitHub Pages site

1. Head over to https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site.
2. Follow and complete each step but ignore the *Next steps* section.
3. I opted to use the default site theme, but you can select another one here :  
https://docs.github.com/en/pages/getting-started-with-github-pages/adding-a-theme-to-your-github-pages-site-with-the-theme-chooser.

#### Hosting a resume

1. Head over to your newly created GitHub Pages repo within your GitHub account. Its name has the format username.github.io.
2. There will be a README.md file along with a folder named docs. Open this docs folder.
3. Open the \_posts folder.
4. Depending on your preference, follow and complete each step at this link for either *Adding a file to a repository on GitHub* or *Adding a file to a repository using the command line*  :  
https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository.

#### Configuring your GitHub Pages site - loose ends

1. Head over to your newly created GitHub Pages repo within your GitHub account. Its name has the format username.github.io.
2. There will be a README.md file along with a folder named docs. Open this docs folder.
3. Open the \_config.yml file
4. I modified lines 21-24, but you can update any of the green highlighted items.
5. Commit your changes.

#### Final product for me
![ass2](https://user-images.githubusercontent.com/92553879/139300138-440d15df-b2ac-467d-af48-635ebd84e30b.gif)

### More Resources :
- Markdown basics  
https://www.markdowntutorial.com/
- Andrew Etter’s book *Modern Technical Writing*  
https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS
- Atom tutorial  
https://flight-manual.atom.io/getting-started/sections/atom-basics/
- Getting started with GitHub  
https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account

### Authors and Acknowledgements :
Credit to [Jekyll](https://jekyllrb.com/) for their templates.  
Credit to [GitHub](https://github.com/) for hosting my site for free.  
Credits to Syed Ali Ahsen Muhammad Jafry, Md Jannatul Nayem, Minh Nam Hai Nguyen, and Akashdeep Singh for their help peer editing.

### FAQs

1. *"Why is Markdown better than a word processor ?"*  
In terms of portability, Markdown is supported by a wide range of software whereas Microsoft (MS) Word is proprietary, so .docx files may only be opened in Word if you want full functionality. Markdown may have a limited set of functions, but they are available on every version so backward compatibility is not an issue. On the other hand, try opening a Word file created from MS Word 2019 with MS Word 95.
2. *"Why is my resume not showing up ?"*  
GitHub notes that it could take up to 20 mins for modifications to reflect on your site, but verify that your resume is a .md file.
