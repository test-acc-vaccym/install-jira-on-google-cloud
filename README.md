# install-jira-on-google-cloud
Get a google cloud instance for free ($300 for free on first sign up)
Create a new VM
To get the link of the jira software, go to https://www.atlassian.com/software/jira/download select the right options of OS type and right click on Download and copy link.
Run this command to download Jira on the newly creted VM using command prompt.
Example, wget [URL]
> wget https://www.atlassian.com/software/jira/download?_ga=2.1113016.825200229.1506046053-328858379.1500225237

Choose the appropriate installation or upgrade option (on the command prompt when asked by installer)
Please choose one of the following:
Express Install (use default settings) [1], Custom Install (recommended for advanced users) [2, Enter], Upgrade an existing JIRA installation [3]
> If you want to set up embeded database then use: 1
> If you want to set up a custom database then use: 2
After completing installation of Jira, you can open Jira in your computer's browser

Now install Google Cloud SQL



Install Java on Google Clould
Follow this page: https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-get-on-debian-8
