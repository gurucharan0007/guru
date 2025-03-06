DAY THURSDAY 06-03-2025

IMPORTANT git commands

git status

// to know the status of floder

git clone <URL>
//to download the repo

git clone https://github.com/neelmyna/vvce_mar25
//to get into and download already done repo

git pull origin main
// command to download the updated repo  from the server to the local machine

to make our computer recognise our git accouny,we must run these 2 conguration commands:
git config --global user.name "gurucharan k v "

git config --global user.email "gurucharanvish@gmail.com"

STEPS TO CREATE A NEW PAT IN GITHUB:

login to github
right to top corner click on your profile
scroll down and click settings
next window, on top left, click personal access tokens, click again on token classic
(Now you may be asked to enter password)
next, Add a note for the new PAT we are creating
select Expiry -> No expiration 
select the Top check box named Repo
Scroll down fully and click the green button ( generate token)
Now, copy the PAT
come to your gmail and mail the Pat to yourself or to one of our account (Mail subject: GIT PAT)

Now , let us sync our Remote Repo with local  repositoryIN other words, we are going to CLONe our Repo using the PAT.by doing so, we can remove REPO without having to Authenticate everytime

