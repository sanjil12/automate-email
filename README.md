# automate-email
in this project we will read the emails from a person's email id and automate the email fetching process to save in local machine
first we need learn about python inbuilt libraries email,imaplib and beautiful soap
for python email documentation-https://docs.python.org/3/library/email.html
for imaplib documentation-https://docs.python.org/3/library/imaplib.html
imaplib consist of three main class , we are using imap4_SSL class for our project for more secure connection
beautiful soap(BS4) is used to fetch the data and to clean the data, as data will be in html format with plain text inside it
loginid and password is needed to run the code
common error while working with gmail-id i.e. 
1.you should allow access to less secure apps from the gmail security settings 
2.allow two step verification process in your gmail account
code for claning the html data and saving on the local machine is added(just remove commented part and add that code to the script)
