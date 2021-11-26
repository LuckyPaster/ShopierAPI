# ShopierAPI
I've done a lot of research until now, but I couldn't see a code that gets a 100% correct response with shopierapi. I quickly wrote a code for it and the response is correct!

# For implementation API
* change api user and api key in **index.php** example: **$shopier = new Shopier('apiuser', 'apikey');**
* change return url on **index.php** and change it from module settings in **shopier** (example for index.php): **die($shopier->run($sipno, $price, 'notify.php'));**
* adjust the index.php according to your wishes, change the username etc.

*
