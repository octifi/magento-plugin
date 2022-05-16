# OctiFi magento plugin latest download

Steps for integration
https://docs.octifi.com/magento-integration-guide



== Changelog ==

= 1.0 =
* Initial release.

== Upgrade Notice ==
= 1.0.2 =
- Country code added to checkout web redirect

= 1.0.3 =
- Saving Checkout token in the order

= 1.0.4 =
- Modal popup option added

= 1.0.5 =
- SDK URL Changed

= 1.0.6 =
- Plugin setting payment type option changed to radio button and changed the labels too.
- Setting the order status as processing for the successful payment instead of completed status.

= 2.0.1 =
- Payment actions(authorize and capture) select option provided.
- If payment option authorize selected, capture will be carried out when order status changed to complete.
- Id payment option capture selected, both authorize and capture will be carried out during the checkout.

= 2.0.2 =
- Bug fixed while displaying error message from payment gateway.

= 2.0.3 =
- Added new feature, now captured status will display in the admin order page and if not captured, admin capture manually.

= 2.0.4 =
- Bug Fixed on automatic capture on order completion

= 2.0.5 =
- Bug Fixed on checkout script rendering, added slashes to the string params

= 2.0.6 =
- Bug Fixed on listing image output
- Bug Fixed on listing price output
- Plugin meta data updated
- TOS links updated

= 2.0.7 =
- changed prfixes
- changed CURL to HHTP API
- changed JS and CSS integration structure


= 2.0.8 =
- changed prfixes
- added sanitization

= 2.0.9 =
- moved shop listing message below price
- removed js console logs
- fixed checkout logo size

= 2.0.10 =
- removed modal pop up functionality
- min summ functionality created
- added option to hide text in archives

= 2.0.11 =
- fixed single product output issue
- changed single product hooks
- fixed JS model layers issue

= 2.1.0 =
- Colour palette change and font change
- Added latitudepay logo
- Renamed octifi to latitudepay

= 2.1.1 = 
- code structure change 

= 2.1.2 =
- Test mode alert added
- css change

= 2.1.3 =

- Learn more - T&C link to change
- Learn more - "We accept all the major bank debit cards"
- Reduce the radius of the Learn more pop up
- select country field added - Select the country dropdown
- Based on selected country - use the respective env variables