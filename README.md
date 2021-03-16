# Homeseer-Postman-Collection
Postman collection for the Homeseer 4 (JSON) API

Tested with: Homeseer 4.1.10.0 (Windows)
From: https://docs.homeseer.com/display/HSPI/JSON+API


![postman screenshot](/_images/HOMESEER.postman_collection.png)



# Setup

1. Get Postman: [here](https://www.postman.com/)
2. Import collection 
    1. Copy collection link: https://raw.githubusercontent.com/DJF3/Homeseer-Postman-Collection/main/HOMESEER.postman_collection.json
    2. In Postman, click "environments" and the "import" button
    3. Click the "Link" tab
    4. Paste the link from step 1
4. Create environment "hsserver" with current value of: http://IP_ADDRESS_OF_HS_SERVER
5. enjoy



# API Calls

System | Status | Control | Get | 
------------ | ------------- | ------------- | -------------
Version | All            | by label        | Locations ALL
Dev Count | All details  | by value        | Categories ALL
Session | location1      | by index        | Counters ALL
Speak   | location2      | by controluse   | Events
.       | Device ref     | device property | Settings
.       | device changed | status value    | Counter
.       |                | Run event name  | Controls


# Notes

- I have not tested this with a remote HS server (through myhs.homeseer.com) 
