# SmartThings
SmartThings Groovy Code for CrossPoint 

Getting SmartThings Ready to Connect to CrossPoint

1. Login to (https://account.smartthings.com/). Use the "Sign in with Samsung" Account link.
2. Goto My Locations and click on your location. Sometimes the site will not automatically select your location without doing this step.
3. After selecting your location goto the My SmartApps menu.
4. Click the New SmartApp button at the top right.
5. Select the From Code option and paste the CrossPoint Groovy code into the box. You can get the Groovy code here (https://github.com/crosspointapp/SmartThings/blob/main/SmartApp).
6. After you paste the code into the box click on the Create button at the buttom left.
7. Click on the App Settings button at the top right.
8. Click the OAuth menu and enable OAuth.
9. Add this URL into the Redirect URI (https://prod.ruleiot.com/verify/smartthings) and click the update button.
10. After you click update you should see the Client ID and Client Secret. These numbers will be added to connect to the CrossPoint app. Please save them and open CrossPoint.

Connecting SmartThings to CrossPoint

1. Login to the CrossPoint App.
2. Goto the CrossPoints menu.
3. Click on the SmartThings connecting button, type in your Client ID and Secret and click the connection button.
4. You should see your devices in the Devices menu and now you can use CrossPoint to control your SmartThings devices.



