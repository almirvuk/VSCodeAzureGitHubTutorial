#<b>Visual Studio Code + GitHub + Azure Tutorial</b>
How to upload web site to <b>Microsoft Azure</b> using Visual Studio Code and GitHub public/private repository.

Requirements for this tutorials:
- DreamSpark, MSDN or BizSpark subscription, or any business account
- Visual Studio Code
- Git source control installed on your PC/Mac/Linux machine 

... and good luck with this tutorial!

<br>
#Step 1. Repository
Make new repository on your GitHub account or you can use this repo with the pull request.


<br>
#Step 2. Make your web site or edit this
Edit code from this repo, or make your own simple web site that you want to upload to Microsoft Azure cloud following this tutorial.

<br>
#Step 3. Make Web App on Azure
Sign into your [Azure Portal](https://portal.azure.com/) and than go to make a new Web App like this:
- In Azure portal navigate to <b>New > Web + Mobile</b>
- Choose <b>Web App</b>
- Enter <b>App name</b> for your new Web App
- <b>Choose Subscription</b> (DreamSpark, MSDN, BizSpark)
- Pick your <b>Resource group</b> (new or existing one)
- Set <b>App service plan/Location</b>
- Pin to dashboard (optional)
- Click <b>Create</b>

<br>
#Step 4. Connect App with GitHub
Find your new Web App on dashboard or in resource group and make sure that it is running, click on it and navigate to <b>All settings</b>.
Under All settings find and navigate to: 
<b> Publishing >  Deployment Source >  Choose Source</b>

In Choose source click on <b>GitHub</b>, after that you need to make sure that Azure is connected with your GitHub account... to do that go to <b>Authorization</b> and follow simple steps to make sure GitHub is now authorised with your Azure account.
Than thhe under <b>Choose project</b> choose which repository/project from GitHub you want to publish on Azure... and click <b>OK</b>.

Make final changes on your local project/web site commit and do push to GitHub from <b>Visual Studio Code's</b> Git integrated tools.
Finally navigate to your Web App URL, if you don't know URL of your Web App. URL is simply a combination of: <b>Web App name + .azurewebsites.net </b>

<br>
#Congrats! Now you have your web site successfully published on Microsoft Azure.
Thank you for your attention &hearts; ... and I hope you find this tutorial helpful for you.
You can find me at:
- [My blog](http://almirvuk.blogspot.ba/)
- [Twitter](https://twitter.com/AlmirVuk)
- [Instagram](https://www.instagram.com/almir_vuk/)
- [Google Play](https://play.google.com/store/apps/developer?id=AV+Development&hl=en/)



