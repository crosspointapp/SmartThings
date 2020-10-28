# SmartThings
SmartThings Groovy Code for CrossPoint 

Getting SmartThings Ready to Connect to CrossPoint

1. Login to (https://account.smartthings.com/). Use the "Sign in with Samsung" Account link. Users in the EU need to use this link (https://graph-eu01-euwest1.api.smartthings.com/).
2. Goto My Locations and click on your location. Sometimes the site will not automatically select your location without doing this step.
3. After selecting your location goto the My SmartApps menu.
4. Click the New SmartApp button at the top right.
5. A New SmartApp configuration page will show, and have the "From Form" tab selected. Select the "From Code" tab instead.
6. Go to the below code repository for the CrossPoint smart app code. Copy and paste the source code into the "From Code" tab on the samsung site, and Create the Smart App. https://github.com/crosspointapp/SmartThings/blob/main/SmartApp.
7. After you paste the code into the box click on the Create button at the buttom left.
8. Click on the App Settings button at the top right.
9. Click the OAuth menu and enable OAuth.
10. Add this URL into the Redirect URI (https://prod.ruleiot.com/verify/smartthings) and click the update button.
11. After you click update you should see the Client ID and Client Secret. These numbers will be needed to connect to the CrossPoint app. Please save them and open CrossPoint on your mobile phone.

Connecting SmartThings to CrossPoint

1. Login to the CrossPoint App.
2. Go to the CrossPoints menu.
3. Click on the SmartThings connecting button, type in your Client ID and Secret and click the connection button.
4. This should take you to the SmartThings login screen. Login again to the Samsung site.
5. Click on your hub name and select the devices that you want to authorize.
6. Click on the Authorize button.
7. You should see your devices in the Devices menu and now you can use CrossPoint to control your SmartThings devices.



