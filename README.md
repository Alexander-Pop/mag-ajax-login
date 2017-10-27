# DigitalPianism_AjaxLogin

Ajax Login &amp; Registration via Popup module for Magento

# Documentation

Everything you need to know can be found here: http://www.digital-pianism.com/en/magento-modules/ajax-popup-login.html

# Magento Connect

https://www.magentocommerce.com/magento-connect/ajax-popup-for-login-registration.html

# Release Notes

## 0.3.1

- Fix a bug where the module would not work with confirmation email enabled: https://github.com/digitalpianism/ajaxlogin/issues/2

## 0.3.0

- Secure all controller calls to use HTTPS
- Implement CORS to be able to call the controller from HTTP

## 0.2.7

- Fix a bug where the meta title of every page would be set to "Create New Customer Account"

## 0.2.6

- Fix a bug where customer registration would not work on Magento < 1.9.0.1

## 0.2.5

- Fix a bug where customer registration would not work on Magento < 1.9.1.0
- Add missing _getUrl to the controller
- Add the popup to the my account link when customer is not logged in

# Description
This extension adds the possibility for frontend Magento users to log in, register and log out via an AJAX popup.

AJAX is a combination of technologies that will let users updating parts of a your web store without reloading the entire page.

For example, when you want to log in with a default Magento installation, clicking the "log in" top link will load a new page (the login page). With AJAX Login, clicking the "log in" top link will display a popup so users can login without reloading a new page.

This module will help you decrease the number of pages your customers need to load to access their account and thus improve their navigation through your website.

Configuration
To enable the module, simply go to System > Configuration > Digital Pianism > Ajax Login > Enabled = Yes then Save

Features
Frontend AJAX popup that handles the login form, the registration form, the forgot your password form and a logout confirmation message.

Design
The module comes with Magento default design (see screenshots).
