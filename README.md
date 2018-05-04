# Bitcoin Simple Shop (V1 forwarding)
This repository contains simple examples of how you can use the apirone.com receive payments API to process bitcoin payments.

Further documentation & explanation can be found at: https://apirone.com/docs/bitcoin-forwarding-api

Show an invoice to the User with a javascript payment button. Once payment is received, page redirects to a status page. When the payment is fully confirmed the page shows the user nutsandbolts.jpg i.e. the product.

This code is intended as educational reference material and is not written for production use.

# Live Demo
http://board.bitcoinexamples.com/

# Instructions
* Clone the git repository into the ROOT of your web server.
* cd /www/receive_payment_php_demo
* chmod 755 ./
* Change URL address, bitcoin wallet and database settings at setup.php
* Navigate to setup.php in your browser
* http://your_site/receive_payment_php_demo/setup.php
* Now the database is initialized open the demo
* http://your_site/receive_payment_php_demo/index.php
