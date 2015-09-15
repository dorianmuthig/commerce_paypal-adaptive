
Commerce PayPal Adaptive
========================

# Purpose 
Drupal Commerce PayPal Adaptive Payments
This is a simplified version of Commerce PayPal Chained

**Warning**: 
This module now automatically calculates the PayPal fees (at the worst rate possible) and adds it to the amount the user will have to pay.

This not allowed when doing business outside of the EU or when using non-EU PayPal accounts. See [section 4.5 of the PayPal user agreement (US)](https://www.paypal.com/webapps/mpp/ua/useragreement-full?country.x=US&locale.x=en_US#4 "PayPal User Agreement - US Version") for details.
Inside the EU, the same relevant section of the user agreement permits it, if you are legally permitted to do so in [section 4.4](https://www.paypal.com/webapps/mpp/ua/useragreement-full?country.x=LU&locale.x=en_US#4 "User Agreement for PayPal Service - EU Version"). This legal permission is not PayPal's decree, and you may not rely on having it. You are usually not allowed, as it may discourage buyers from using PayPal as the payment method, which is one of the conditions you agree to for using them. If you want to do this, please consult a lawyer, if you are allowed to. If you ignore this warning, your account may be suspended, and in the worst case, your funds be forfeit.

# Commerce PayPal Adaptive Simple Payments
This module is a fork of `commerce_paypal_simple`

# Commerce Paypal Chained

Information about About PayPal Chained
1. https://drupal.org/node/2082691
2. https://github.com/chrisolof/commerce_paypal_chained

# `commerce_paypal_simple`
1. https://github.com/PlusGenie/commerce_paypal_simple


# How to Use 
1. Remove receivers from Paypal Chained
2. When a buyer buy something, it will automatically pay to the product owner.
So you must fill in your PayPal account when you sign up a Drupal site

![alt text](../../../images/blob/master/RegisterPaypalAccount.png?raw=true)
