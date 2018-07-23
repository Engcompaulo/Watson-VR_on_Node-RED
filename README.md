# Watson Visual Recognition on Node-RED

Use Watson Visual Recognition standard or custom image classifiers using the Node-RED interface 

## SETUP STEPS:

### 1. Create instances of these IBM Cloud Services:

#### Node-RED Starter Kit: 

https://console.bluemix.net/catalog/starters/node-red-starter

#### Watson Visual Recognition:

https://console.bluemix.net/catalog/services/watson-vision-combined

### 2. Open the Node-RED Flow Editor from the Starter Kit and import the code from the .json file in this repository.

#### Node-RED Flow:

![alt text](https://i.imgur.com/oG8FYYF.png)

### 3. Setup the Watson VR nodes API-KEYs.

![alt text](https://i.imgur.com/DoyHIjv.png)


### 4. Usage Observations:

I. Insert some image URL that ends with '.jpeg' or '.png';
II. Choose a custom classifier id (all avaiable custom classifier-ids from your Watson VR service will be showed below the fields) or leave 'default' as classifier id, otherwise the WebApp won't work.
III. Hit Submit button and enjoy the results!
