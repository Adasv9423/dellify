# Dellify

Full Stack E-commerce app for android and ios  along with Admin Panel.

## Features
- Email & Password Authentication
- Persisting Auth State
- Searching Products
- Filtering Products (Based on Category)
- Product Details
- Rating
- Getting Deal of the Day
- Cart
- Checking out with Google/Apple Pay
- Viewing My Orders
- Viewing Order Details & Status
- Sign Out
- Admin Panel
    - Viewing All Products
    - Adding Products
    - Deleting Products
    - Viewing Orders
    - Changing Order Status
    - Viewing Total Earnings
    - Viewing Category Based Earnings (on Graph)


## Running Locally
After cloning this repository, migrate to root folder. Then, follow the following steps:
- Create MongoDB Project & Cluster
- Click on Connect, follow the process where you will get the uri.- Replace the MongoDB uri with yours in ```server/index.js```.
- Head to ```lib/constants/global_variables.dart``` file, replace <yourip> with your IP Address. 
- Create Cloudinary Project, enable unsigned operation in settings.
- Head to ```lib/features/admin/services/admin_services.dart```, replace ```denfgaxvg``` and ```uszbstnu``` with your Cloud Name and Upload Preset respectively.

Then run the following commands to run your app:

### Server Side
```bash
  cd server
  npm install
  npm run dev (for continuous development)
  OR
  npm start (to run script 1 time)
```

### Client Side
```bash
  flutter pub get
  open -a simulator (to get iOS Simulator)
  flutter run
```

## Tech Used
**Server**: Node.js, Express, Mongoose, MongoDB, Cloudinary

**Client**: Flutter, Provider
    
## APP PREVIEW FOR USER-
![register_page](https://github.com/Adasv9423/dellify/assets/76847225/69cc433b-cc22-46a2-ac5b-aade2d2e1874)
![ui_user_dellify](https://github.com/Adasv9423/dellify/assets/76847225/27ae4a1a-58d2-4493-b35a-b2cc1a29bb70)
![category_mobiles](https://github.com/Adasv9423/dellify/assets/76847225/a69cd9f5-7305-492d-b4a2-64024073138c)
![category](https://github.com/Adasv9423/dellify/assets/76847225/3b698cf8-4d2c-47fa-b44d-0e5cd9910f6c)
![dellify_rsting_without](https://github.com/Adasv9423/dellify/assets/76847225/a7d5e18a-2e80-44f6-ae61-c5f02dc766b1)
![dellify_order](https://github.com/Adasv9423/dellify/assets/76847225/ea8ad27a-1ce6-45a8-9875-6e5f81df7d93)
![user_cart_detsis](https://github.com/Adasv9423/dellify/assets/76847225/a15188b2-4471-47ed-a3c4-b40e8c87d23f)
![showing_orders](https://github.com/Adasv9423/dellify/assets/76847225/3ddf5e2d-c9eb-4fae-9df3-4061ed883baa)


