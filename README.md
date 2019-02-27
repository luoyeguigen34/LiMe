# LiMe
LiMe is a communication app which allows you to send messages whenever and wherever you are, 24 hours a day!

## Full name
The Li Xin Messenger

## Version
- C_v 0.6.2
- S_v 0.6.2

```
 _______________________
/    Finally, v0.6.2!   \
|  _     _ __  __       |
| | |   (_)  \/  | ___  |
| | |   | | |\/| |/ _ \ |
| | |___| | |  | |  __/ |
| |_____|_|_|  |_|\___| |
\                       /
 -----------------------
        \   ^__^
         \  (oo)\_______
            (__)\ LiMe  )\/\
                ||----w |
                ||     ||
```

## Platform compatibility: 
- macOS
> If you would like to use it with windows, you should clone this repo and rebuild it with windows.

## Protocol
为了使LiMe更好地工作，我们设定了一个应用层协议

## The Server GUI
![](./ScreenShots/LiMeServer.png)

## Client

The Login GUI, also the welcome page

![](./ScreenShots/LiMeLogin.png)

The Register GUI

![](./ScreenShots/LiMeRegister.png)

The User Agreement (HTML parsing)

![](./ScreenShots/LiMeAgreement.png)

The Chat GUI of user @lixin, the friend list is on the left side of the panel
![](./ScreenShots/LiMeChatLixin.png)

The Chat GUI of user @test

![](./ScreenShots/LiMeChatTest.png)

### The Group Chat

![](./ScreenShots/LiMeGroupChat.png)

### The File Transmission

![](./ScreenShots/LiMeChatFile.png)

## Data persistence

MySQL table structure
![](./ScreenShots/TableStructure.png)

## Emails you might get from the server

Registration Confirmation
![](./ScreenShots/EmailCfmReg.png)

Banned Notification
![](./ScreenShots/EmailNtfBan.png)

Password Reset
![](./ScreenShots/EmailRstPwd.png)

## TODO
- [ ] Gradle the project
- [ ] Use HTML to render the email content
- [ ] Use hibernate or Mybatis as a persistence framework
- [ ] The process bar for the file transmission
- [ ] A fancy website for LiMe
- [x] Store the password on the server with MD5
- [x] Local password storage encrypted with AES using random key, random key stored with AES digested with MD5
- [x] Transport the message with AES and keys digested with MD5
- [X] Open group chat for all users
- [x] Enable user to reset password via a server-sent Email
- [x] Redirect LiMe to the new domain name
- [x] Email is should be a unique key (LiMeSeedRecoverPassword)
- [x] The file transmission function
- [x] Use database to validate and manage the user
- [x] Blur Agreement Frame
- [x] HTML parsing and rendering
- [x] Version number increase

## Test Quote
Fate Whispers To The Warrior,

“You Cannot Withstand This Storm”

And The Warrior Whispers Back,

“I Am The Storm”