# QRCode #Authentication using sms and email
Bus pass system
This system final yr btech cse project on ASP.NET by kunal bhardwaj,rajesh rana and rahul p kumar. I am providing QR code scanning of the bus pass where we can scan code and it need to be unique for each bass pass holders.
It make paper less events which simplifies process,reduce costs.Transferring sms provider credentials and impleMent of data transfer to sms provider.
The index action method in manage controller sets status message based on your previous action and provides links to your local password or add local account.
Addphonenumber action method display dialog box to enter phone number that receive sms messages.
The generatechangephonenumbermethod generates security token which will set in sms message.Smsservice.sendsync method to is asynchronously, then app is redirected to verifyphonenumber action method 
where we can add verification code.The changephonenumberasyn method checks posted security code.applicationusermanager create method configures lock out.
TO see the updated files check latest commits of.csfiles and txt files which having a sms alert security.
Merged master branch with new branch included.
