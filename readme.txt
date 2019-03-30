=== WooCommerce Payment Gateway - Momo ===
Contributors: freelancerviet.net
Donate link: http://freelancerviet.net/
Tags: WooCommerce, Payment, Gateway, Momo
Requires at least: 4.7
Tested up to: 5.1.1
Requires PHP: 5.6
Requires WooCommerce: 3.0
Stable tag: 2.1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Allow woocommerce pay with MOMO of momo.vn

== Description ==

This plugin support payment gateway Momo.  


== Installation ==

= Installing The Payment Gateway Plugin =
* Download the plugin zip file.
* Login to your WordPress Admin. Click on Plugins | Add New from the left hand menu.
* Click on the “Upload” option, then click “Choose File” to select the zip file from your computer. Once selected, press “OK” and press the "Install Now" button.
* Activate the plugin.
* Open the settings page for WooCommerce and click the "Payment Gateways," tab.
* Click on the sub tab for "Momo."
* Configure your Inspire Commerce Gateway settings. See below for details.

__Note: This plugin requires that you have an SSL certificate installed and active on your site.__

= Obtain Credentials from Inspire Commerce Gateway =
To setup your Inspire Commerce Gateway you will need to enter your account Username and Password.

= Connect to WooCommerce =
To configure the plugin, go to __WooCommerce > Settings__ from the left hand menu, then the top tab “Payment Gateways”. You should see __"Inspire"__ as an option at the top of the screen. 
__*You can select the radio button next to this option to make it the default gateway.*__

* __Enable/Disable__  – check the box to enable Inspire Commerce.
* __Title__  – allows you to determine what your customers will see this payment option as on the checkout page.  
* __Description__  – controls the message that appears under the payment fields on the checkout page. Here you can list the types of cards you accept. 
* __Username__  – enter the API username you created in your Inspire Commerce Gateway account. 
* __Password__  – enter the API password you created 
* __Sale Method__  – select the sale method you prefer – your options are: ‘Authorize Only’ or ‘Authorize & Capture.  ‘Authorize Only’ will authorize the customer’s card for the purchase amount only.  ‘Authorize & Capture’ will authorize the customer’s card and collect funds.
* __Card Types__  - make sure to highlight all the credit card options in blue (using either the shift or control button) 
* __CVV__  – check the box to require customers to enter their credit card CVV code
* __Billing Information Storage__  – this is an optional feature of the gateway.  In order to use this feature you will have to sign up for our Customer Vault.
* __Save Changes.__ 

== Screenshots ==

1. Easily accept credit card payments on your own branded page.

2. Here is a close up of the payment form as seen by your customers (it is fully editable and already branded to perfection for all WooThemes.com themes).  Notice that advanced features such as saving credit cards securely via the Inspire Commerce card vault are available if you choose to activate them in the admin area.  The module even works flawlessly with the WooCommerce subscriptions module.

3. While you can do a LOT on the back end, here is a simple screen shot of the two most important data points... your API username and password which are used to connect the gateway to your shopping cart. 

== Frequently Asked Questions ==

= Do I need a merchant account before I can use the Inspire Commerce gateway plugin? =
Yes.  In order to use this plugin you will need a merchant services account.  Inspire Commerce offers merchant accounts. For more information, please visit: http://www.inspirecommerce.com. If you already have a merchant account set up, chances are our gateway will integrate with it.  Send us an email: support@inspirecommerce.com or call our office: 800-261-3173 to find out more.

= What is the cost for the gateway plugin? =
This plugin is a FREE download, however it does have monthly and per transaction costs.  The gateway is $10/month plus $0.10 per transaction for the basic gateway features.  We do also offer value added features for an additional fee.  For more information: support@inspirecommerce.com 

= Inspire Commerce is not showing up as a payment method - help! =
For security purposes, this plugin requires an active SSL connection via a secure https page to view this option on your payment pages.

= Does the plugin work with the WooCommerce subscription extension? =
Yes.  It works as long as the card vault functionality is activated in the gateway, and is turned on inside the WooCommerce payment gateways settings for Inspire Commerce.

== Changelog ==
 
= 1.0 =
* First Release.
