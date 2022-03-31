So, this is pretty straightforward, you'll open it, it'll ask you for a passcode for a private key, your email and your password from your spotify account, yes I know it sounds bad but I ain't stealing nothing from you fr.   
After inserting your email and password, the app will automaticaly save them into 2 separate RSA encrypted files (rsa is one of the safest encryption methods), then the app will check if your spotify is open, if not it'll ask you to open it, after that it'll check if you have the spotify token, if not, it'll automatically generate one using your email and password that'll be decrypted (but not creating a file with them decrypted).  
After all of that, everytime you play a new song a pretty notification like the one in the image will appear.  
  
![github](https://user-images.githubusercontent.com/91756430/161148339-ba25d13e-33fe-48d1-a67b-07e7e700035f.png)  
  
IMPORTANT:  
there might be a slight bug while opening chrome and getting the token since the method I used to get it depends on x and y positions of the mouse, so if you run into any trouble with that, access the sit I'll leave bellow, create your token as user-read-currenlt-playing and copy it to your clipboard, then run the app.
