#About Ubercart module
Drupal is one of the leading CMS platforms in the world, ranking 3rd after Wordpress and Joomla; Ubercart is Drupal’s most popular eCommerce plugin. As part of our dedication to making payments human again we built an easy-to-use payment module for Drupal so our merchants can accept payments globally with a single, simple integration.

###Versions
* Drupal from 7.* and newest
* Ubercart from 3.* and newest

#Installation
####IF YOU DO NOT HAVE A MERCHANT ACCOUNT REGISTERED AT PAYMENTWALL, PLEASE SIGN UP BY COMPLETING THE STEPS BELOW.
* If you don't have a Paymentwall Merchant Account yet, please [Sign Up](https://api.paymentwall.com/pwaccount/signup?source=ubercart&mode=merchant)

* Fill out the Sign Up Form

![Sign Up step 1](https://wallapi.com/content/design/files/developers/instructions/_general/new_step1_signup.png)

* Please enter your Company Name and website URL

![Sign Up step 2](https://wallapi.com/content/design/files/developers/instructions/_general/new_step2_signup.png)

* Press the **Continue** button. Your Paymentwall Merchant Account has been created

####IF YOU ALREADY HAVE A MERCHANT ACCOUNT REGISTERED AT PAYMENTWALL.

* After you log in, please go to **My Applications** tab. You will see your first application already created. Please note the Application Key and Secret Key. You will need them later to finish the application setup.
![My Applications](https://wallapi.com/content/design/files/developers/instructions/_general/new_step3_addapplication.png)

* Press the **Settings** button. Please select "Digital Goods" under "Your API".
* Set the **Pingback URL** to: http://[path-to-ubercart]/paymentwall_pingback.
* Set the **Signature Version** to **1**.
* Click **Save Changes**.

![Settings](https://wallapi.com/content/design/files/developers/instructions/_general/new_step4_settings.png)

* Press the **Widgets** button, **Add New Widget**, scroll down and select **Paymentwall Multi** widget.

![Paymentwall Multi](https://wallapi.com/content/design/files/developers/instructions/_general/new_step6_widget.png)

####INSTALL PAYMENTWALL FOR UBERCART

* Go to http://[path-to-ubercart]/admin/modules and install the Paymentwall module.

![Install New Module](https://wallapi.com/content/design/files/developers/instructions/Ubercart/ubercart_step1.png)

* Activate the module at http://[path-to-ubercart]/admin/modules in the section **Ubercart -> Payment**. Press the **"Save Configuration"** button.

![Activate Paymentwall module](https://wallapi.com/content/design/files/developers/instructions/Ubercart/ubercart_step2.png)

* Now Paymentwall module is installed, but not activated as a payment gateway. Please activate it at http://[path-to-ubercart]/admin/store/settings/payment. Press the **"Save Configuration"** button.

![Activate payment gateway](https://wallapi.com/content/design/files/developers/instructions/Ubercart/ubercart_step3.png)

* Click the **Settings** link on payment methods configuration page http://[path-to-ubercart]/admin/store/settings/payment and fill all fields. You can find the Application key and Secret key in your **Paymentwall Merchant Account -> My Applications**. The Widget code is available in your **Paymentwall Merchant Account -> My Applications -> Widgets**.

![Activate Paymentwall module](https://wallapi.com/content/design/files/developers/instructions/Ubercart/ubercart_step4.png)

* Press the **"Save Configuration"** button.

####SUBMIT THE APPLICATION FOR APPROVAL

Once all the settings have been properly configured, go back to your **Paymentwall Merchant Area -> My Applications** and submit the application for approval by pressing the **Submit For Review** button.

Your application will be approved shortly once we review the integration and make sure that everything is running smoothly for your users.

If you have any questions, please feel free to contact us at devsupport@paymentwall.com

#License
The MIT License (MIT)

Copyright (c) 2010-2014 Paymentwall, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.