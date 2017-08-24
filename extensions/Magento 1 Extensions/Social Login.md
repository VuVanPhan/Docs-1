**SOCIAL LOGIN - MAGENTO 1** 
----------

**Version 3.1**
Confidential Information Notice. Copyright2016. All Rights Reserved. Any unauthorized reproduction of this document is prohibited. This document and the information it contains constitute a trade secret of Magestore and may not be reproduced or disclosed to non-authorized users without the prior written permission from Magestore. Permitted reproductions, in whole or in part, shall bear this notice.
 
## Introduction
----------
The fact that a lot of information is required when creating a new account can discourage Customers from doing so on your site. However, most of them already have social accounts such as Facebook, Google, Yahoo, Twitter, LinkedIn, etc. Why don’t you enable them to use such accounts to log in by using our Social Login extension? Customers just need to click on the account button they like, and then enter their username and password!

## How to use
----------
### Show Social Login buttons at many positions in front-end

 - Show the Social Login buttons in the Header

(image 1)

 - Show the Social Login buttons below Customer login form

(image 2)

- Show the Social Login buttons below Customer registration for

(image 3)

### Customer can log in to web-shop by many social network accounts

- Log in using Facebook account

(image 4)

- Log in using Instagram account

(image 5)

- Log in using Twitter account

(image 6)
- Log in using Amazon account

(image 7)

- Log in using Google account

(image 8)

- Log in using Yahoo account

(image 9)
- Log in using LinkedIn account

(image 10)

- Log in using MyOpenId account

(image 11)

- Log in using LiveJournal account

(image 12)

- Log in using AOL account

(image 13)

- Log in using WordPress account

(image 14)

- Log in using Clavid account 

(image 15)

- Log in using Orange account

(image 16)

- Log in using FoursQuare account

(image 17)

- Log in using Live account

(image 18)

- Log in using StackExchange account

(image 19)

- Log in using Vk account

(image 20)

## How to configure
-----------------
### General configuration

 - Go to **System > Configuration**
 - Select **Social Login** tab
 - Select **General Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Activate/ Deactivate extension|
|2|Shown Posotion|Header|Position of Social Login buttons in frontend|
|3|Shown Direction|Left to Right| Direction of Social Login buttons in frontend|
|4| Number of visible buttons|4| The number of button visible, others will be shown only when customer hovers “Other login”|

After filling data into the configuration fields, click on the **Save Config** button to save your work.

### Specified configuration

#### Facebook Login Configuration

 - Go to **Social Login > Settings**
 - Select **Facebook Login Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/ Hide Facebook Login button|
|2|Application ID|124951910915…| Facebook application ID **(*)**|
|3|Application Secret|c04561f15ce94894...| Facebook application secret **(*)**|
|4|Send Password To Customer|Yes| Send account info to customer after logging in by using Facebook Login|
|5|Sort order|1|The order of buttons displaying in the list|

After filling data into the configuration fields, click on the **Save Config** button to save your work.

**(*)** **How do I get the Facebook application ID and application secret?**
**Step 1**: Go to page: https://developers.facebook.com/apps/?action=create and then choose “Add a New app”

(image 21)

After that, you need to fill in your contact email and choose the category of app you are creating (Apps for Pages). Remember to click “Skip quick start”

(image 22)

**Step 2**: After clicking creating App ID, you will be moved to a setting page in which you have to fill in your app domain, contact email and Site URL (please click “+Add Platform”) 

(image 23)

In this step, please notice that although your app has been created, it can only get your account information. If you want to get information from other Facebook accounts, you have to publicize your app. This means you need to go to “App Review” tab and choose “Yes”

(image 24)

**Step 3**: After finishing, let’s come back to “Settings” page or “Dashboard” page to get your App ID and App Secret

#### Instagram Login Configuration

 - Go to **System > Configuration**
 - Select **Social Login** tab
 - Select **Instagram Login Configuration** section
 - The configuration fields are listed as follows 

|No|Field|Sample|Description|
|----|------|:--------:|-------------|
|1|Active|Yes|Show/Hide Instagram Login button|
|2|Client ID|d2b4b9adbbb0…|Instagram application ID **(*)**|
|3|Client Secret|f506f959f736460…|Instagram application Secret **(*)**|
|4|Redirect Url|http://demo.magestore.com/social-login/dev/index.php/admin/sociallogin/Instagramlogin/login/|Use this link for redirect url field when registering with Instagram API|
|5|Sort Order|3|The order of buttons displaying in the list|

After filling data into the configuration fields, click on **Save Config** button 
**(*)** **How do I get Instagram Client Id and Client Secret?**
**Step 1**: Go to page: http://instagram.com/developer/clients/manage/ and click “Register a New Client”

(image 25)

**Step 2**: Fill in required information. 

(image 26)

Notice that when you are required to provide the valid redirect URLs, it is in the backend – Instagram tab that you can get this link. 

(image 27)

**Step 3**: After finishing these 2 steps, you will see a notification appearing right after the title Manage Clients that you have registered successfully. You can get your app ID and client secret on the same page. 

(image 28)

#### Twitter Login Configuration

 - Go to **Social Login > Settings**
 - Select **Twitter Login Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|:--------:|-------------|
|1|Active|Yes|Show/ Hide Twitter Login button|
|2|Client ID|hCDOZSI5J5RAe7…| Twitter Consumer Key (*)|
|3|Client Secret|UbJRjdzf5mGfIWI…| Twitter Consumer Secret (*)|
|4|Login Notice|If you have an account on {{store}}, please login, otherwise register a new account to connect to Twitter| Message displayed after customers log in by Twitter account|
|5|Sort Order|2|  The order of buttons displaying in the list|

After filling data into the configuration fields, click on the **Save Config** button

**(*) How do I get the Twitter Consumer ID and Application Secret?**
It’s much easier to create an application with Twitter 
**Step 1**: Let’s go to page https://apps.twitter.com/app/new and fill in your app information. 
In order to get callback URL that is required, please take it from your backend. 

(image 29)

At the end of the setting page, you will see a box with the Twitter developer agreement on which you need to tick Yes. 

(image 30)

**Step 2:** Click “Keys and Access Tokens” tab to get Consumer Key and Consumer Secret

(image 31)

#### Amazon Login Configuration

 - Go to **System > Configuration**
 - Select **Social Login** tab 
 - Select **Amazon Login Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/Hide Amazon Login button|
|2|Client ID|amzn1.application…| Amazon application ID (*)|
|3|Client Secret|7aa4a8c4f5bed1e6c| Amazon application Secret (*)|
|4|Allowed Return URLs|https://demo.magestore.com|Use this link for Allowed Return URLs field when registering with Amazon API|
|5|Send Password To Customer|Yes|Allow sending password to customer after successful register|
|6|Sort Order|4|The order of buttons displaying in the list|

After filling data into the configuration fields, click on the **Save Config** button 

**(*) How do I get Amazon Client Id and Client Secret?**
Before getting started, remember that Amazon only works with https protocol. This means your website cannot connect with Amazon if it doesn’t have a sever that uses https protocol.

**Step 1**: Go to Amazon manage app page: https://login.amazon.com/manageApps  and click “Register new application”:

(image 32)

Fill in your name, description and Privacy Notice URL which actually is your domain:

(image 33)

In Web settings section, there are 2 optional field which are “Allowed JavaScript Origins” and “Allowed Return URLs”. Actually they are your domain and your website URL respectively.. 

(image 34)

**Step 2**: Get your Client ID and Client Secret

#### Google Login Configuration

 - Go to **Social Login > Settings**
 - Select **Google Login Configuration** section
 -  The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/ Hide Google Login button|
|2|Client ID|bMDKA5J5RAe7…|Google Client ID (*)|
|3|Redirect URL|http://demo-extension.magestore.com/sandbox/social-login/index.php/sociallogin/gologin/user/|Please use this link for redirect url field when registering with Google API |
|4|Client Secret|7Db82kVbLEKav2…|Google Client Secret (*)|
|5|Send Password To Customer|Yes|Send account info to customers after logging in by using Google account|
|6|Sort Order|3|The order of buttons displaying in the list|

After filling data into the configuration fields, click on the **Save Config** button to save your work. 

**(*) How do I get the Google Consumer Key and Consumer Secret?**
**Step 1**: Go to https://cloud.google.com/console  or https://console.developers.google.com/project and then click “Create project” as demonstrated below.

(image 35)

After that, fill in your Project Name and then click Create:

(image 36)

**Step 2**: Come to Dashboard and “Enable and manges APIs”

(image 37)

**Step 3**: Click “Credentials” tab and you will see 3 subtitles as demonstrated below. Please click “OAuth consent screen” tab on which you need to fill in your Product name shown to users and then click Save. 

(image 38)

**Step 4**: Back to the subtitle Credential, after clicking “add credentials” button, you will see several choices. Please Choose “OAuth client ID” and “Web application” afterwards. 

(image 39)

Then, fill in all information required. 

(image 40)

Note that you need to get “Authorized redirect URIs” from your backend

(image 41)

**Step 5**: Get your Client IP and Client Secret

(image 42)

#### LinkedIn Login Configuration

 - Go to **Social Login > Settings**
 - Select **LinkedIn Login Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/ Hide Linkedin Login button|
|2|Client API|7gxz5hdq4h8e|LinkedIn Consumer Key (*)|
|3|Client Secret|KF2zb7tzMvXIvcu8|LinkedIn Consumer Secret (*)|
|4|Send Password To Customer|Yes|Send account info to customer after logging in by using LinkedIn account|
|5|Confirm Password|No|Require password to be confirmed or not|
|6|Sort Order|4|The order of buttons displaying in the list|

After filling data into the configuration fields, click on the **Save Config** button

**(*) How do I get the LinkedIn Consumer Key and Consumer Secret?**
**Step 1**: Go to page: https://www.linkedin.com/secure/developer and click “Create application

(image 43)

Please fill in required information. Note that **the app logo must be of same height and width**

(image 44)

After that, tick “LinkedIn API terms of  Use” and submit your form. 

(image 45)

**Step 2**: Get Client ID and Client Secret. You will see some other fields but there’s no need for you to fill in
(image 46)

#### Yahoo Login Configuration

 - Go to **Social Login > Settings**
 - Select **Yahoo Login Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/ Hide Yahoo Login button|
|2|Application ID|CbMx…|Yahoo application ID **(*)**|
|3|Send Password To Customer|Yes|Send account info to customer after logging in by using Yahoo account|
|4|Consumer Key|bMDKA5J5RAe7…|Yahoo Consumer Key **(*)**|
|5|Consumer Secret|7Db82kVbLEKav2…|Yahoo Consumer Secret (*)|
|6|Sort Order|6|The order of buttons displaying in the list|

After filling data into the configuration fields, click on the **Save Config** button.

**(*) How do I get the Yahoo Application ID, Consumer Key and Consumer Secret?**
**Step 1**: Go to page: https://developer.yahoo.com/apps/create/
Then, create application by filling in all required information. 
(image 47)

In the field API permissions, please tick “Profiles/Read Write Public and Private”

(image 48)

**Step 2**: Get your Client ID and Client Secret:

(image 49)

#### AOL Login Configuration

 - Go to **Social Login > Settings**
 - Select **AOL Login Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/Hide AOL Login button|
|2|Send Password To Customer|Yes|Send account info to customer after logging in by using AOL account|
|3|Sort Order| 6|The order of buttons displaying in the list|

(image 50)

After filling data into the configuration fields, click on the **Save Config** button.

#### WordPress Login Configuration

 - Go to **Social Login > Settings**
 - Select **WordPress Login Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/Hide WordPress Login button|
|2|Send Password To Customer|Yes| Send password info to customer after logging in by using AOL account|
|3|Sort Order|7|The order of buttons displaying in the list|

(image 51)

After filling data into the configuration fields, click on the **Save Config** button.

#### MyOpenId Login Configuration

 - Go to **Social Login > Settings**
 - Select **MyOpenId Login Configuration** section
 - The configuration fields are listed as following

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/Hide MyOpenId Login button|
|2|Send Password To Customer|Yes| Send password info to customer after logging in by using MyOpenId account|
|3|Sort Order|7|The order of buttons displaying in the list|

(image 52)

After filling data into the configuration fields, click on the **Save Config** button.

#### Livejournal Login Configuration

 - Go to **Social Login > Settings**
 - Select **Livejournal Login Configuration** section
 - The configuration fields are listed as following

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/Hide Livejournal Login button|
|2|Send Password To Customer|Yes\Send account info to customer after logging in by using Livejournal account|
|3|Sort Order|7|The order of buttons displaying in the list|

(image 53)

After filling data into the configuration fields, click on the **Save Config** button.

#### Clavid Login Configuration
	
 - Go to **Social Login > Settings**
 - Select **Clavid Login Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/Hide Clavid Login button\
|2|Send Password To Customer|Yes|Send account info to customer after logging in by using Clavid account|
|3|Sort Order|10|The order of buttons displaying in the list|

(image 54)

After filling data into the configuration fields, click on the **Save Config** button.

#### Orange Login Configuration

 - Go to **Social Login > Settings**
 - Select **Orange Login Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/Hide Orange Login button|
|2|Send Password To Customer|Yes|Send account info to customer after logging in by using Orange account|
|3|Sort Order|11|The order of buttons displaying in the list|

(image 55)

After filling data into the configuration fields, click on the **Save Config** button.

#### FoursQuare Login Configuration
	

 - Go to **Social Login > Settings**
 - Select **FoursQuare Login Configuration** section
 - The configuration fields are listed as following

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/Hide FoursQuare Login button|
|2|Client Key|bMDKA5J5RAe7…	|FoursQuare Client Key (*)|
|3|Client Secret|7Db82kVbLEKav2…|FoursQuare Client Secret (*)|
|4|Send Password To Customer|Yes|Send account info to customer after logging in by using AOL account|
|5|Sort Order|12|The order of buttons displaying in the list|

After filling data into the configuration fields, click on the **Save Config** button.

**(*) How do I get the FoursQuare Client Key and Client Secret?**
**Step 1**: Go to page: https://foursquare.com/developers/apps or this page: https://foursquare.com/developers/register and click “Create a new app
You will be required to fill in your website’s information:

(image 56)

You can skip other information as below:

(image 57)

**Step 2**: Save and get app’s client and secret:

(image 58)

#### Windows Live Login Configuration

 - Go to **Social Login > Settings**
 - Select **Windows Login Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/Hide Windows Live Login button|
|2|Client Key|bMDKA5J5RAe7…|Windows Live  Client Key (*)|
|3|Client Secret|7Db82kVbLEKav2…|Windows Live Client Secret (*)|
|4|Sort Order|13|The order of buttons displaying in the list|

After filling data into the configuration fields, click on the **Save Config** button

**(*) How do I get the Windows Live Client Key and Client Secret?**
**Step 1**: Go to this page:  
https://account.live.com/developers/applications/create
Then, fill in your App name

(image 59)

**Step 2**: Get Rediect URLs from your backend and set it into “Rediect URLs” box

(image 60)

(image 61)

**Step 3**: Get “Application Id” and “Application Secret” at header

(iamge 62)

#### Persona Login Configuration

 - Go to **Social Login > Settings**
 - Select **Persona Login Configuration** section
 - The configuration fields are listed as following

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/Hide Persona Login button
|2|Send Password To Customer|Yes|Send password info to customer after logging in by using Persona Login|
|3|Sort Order|15|The order of buttons displaying in the list|

(image 63)

After filling data into the configuration fields, click on the **Save Config** button.

#### Stack Exchange Login Configuration
	
 - Go to **Social Login > Settings**
 - Select **Stack Exchange Login Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/Hide Stack Exchange Login button
|2|Send Password To Customer|Yes|Send account info to customer after logging in by using Stack Exchange Login|
|3|Sort Order|15|The order of buttons displaying in the list|

(image 64)

After filling data into the configuration fields, click on the **Save Config** button.

#### Vk Login Configuration

 - Go to **Social Login > Settings**
 - Select **Vk Login Configuration** section
 - The configuration fields are listed as follows

|No|Field|Sample|Description|
|----|------|--------|-------------|
|1|Active|Yes|Show/Hide Windows Live Login button
|2|App ID|4125434|Vk application Key (*)|
|3|Secure Key|VGqJFZ0UozvmjpqRthyS|Vk secure Key (*)|
|4|Send Password To Customer|Yes|Send password info to customer after logging in by using Vk Login|
|5|Sort Order|20|The order of buttons displaying in the list|

After filling data into the configuration fields, click on the **Save Config** button.
**(*) How do I get the Vk App ID and Secure Key?**
**Step 1**: Go to page: http://vk.com/editapp?act=create and then fill in the required information as below:

(image 65)

**Step 2:** You need to fill in your phone number and then get the confirmation code:

(image 66)

**Step 3**: Click my app and start your setting:

(image 67)

You can get your Application ID and Secure key on “Settings” tab:

(image 68)


### Show the Social Login buttons in the different positions

 - The extension allows you to choose among 5 positions to show the Social Login buttons as following.
- Header
- Above customer login form
- Below customer login form
- Above customer registration form
- Below customer registration form

 - Also, you can show the Social Login buttons in other positions by following these steps below.
- Open the file .phtml which contains the position that you want to show login buttons.
- Insert the code below into that file.


``` <?php echo $this->getLayout() >createBlock("Magestore\Sociallogin\Block\Buttons")->setTemplate("Magestore_Sociallogin::buttons.phtml")->setNumberButtonShow(4)->toHtml(); ?>```

 - Another way
- In back-end, open the CMS page which contains the position that you want to show login buttons.
- You can put a social login button block on a CMS page. Here is an example that we put a login block with 4 buttons. Replace "4" in this code with the number of buttons you want to show.



```{{block class="Magestore\Sociallogin\Block\Buttons" name="buttons.sociallogin" template="Magestore_Sociallogin::buttons.phtml" number_button_show="4"}}```

After finishing your configuration, click on the **Save Config** button to save your work.