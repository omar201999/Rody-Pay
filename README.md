# Rody-Pay
Rody Pay is a mobile application developed using Flutter. It supports both Android and IOS.

Rody Pay is a Online Bank application.Users can create their own card and can keep track of all transactions on that card

## Table of contents
- ### [main packages used](https://github.com/omar201999/Rody-Pay/blob/main/README.md#main-packages-used-1)
- ### [Folder structure](https://github.com/omar201999/Rody-Pay/blob/main/README.md#folder-structure-1)
- ### [Screenshots](https://github.com/omar201999/Rody-Pay/blob/main/README.md#screenshots-1)
- ### [Google Play Store](https://github.com/omar201999/Rody-Pay/blob/main/README.md#google-play-store-1)

## Main packages used
- [flutter_bloc](https://pub.dev/packages/flutter_bloc) as state management
- [shared_preferences](https://pub.dev/packages/shared_preferences) to handle caching data
- [flutter_offline](https://pub.dev/packages/flutter_offline) A tidy utility to handle offline/online connectivity
- [flutter_screenutil](https://pub.dev/packages/flutter_screenutil) for adapting screen and font size
- [dio](https://pub.dev/packages/dio) A powerful Http client for Dart
- [google_maps_flutter ](https://pub.dev/packages/google_maps_flutter) provides a Google Maps widget.


## Folder structure
I have applied clean archeticture concept and here is the basic folder structure:

core folder structure that flutter provides:

```
rody_pay
├── android
├── assets
├── build
├── ios
├── lib
└── test
```


Here is the folder structure I have been using in this project:
```
lib
├── business_logic
├── constants
├── data
├── presentation
└── main.dart
```

### business_logic
This folder containes the business logic of the application specificly state management.

```
business_logic
├── global_cubit
└── home-layout_cubit
└── login_cubit
└── registration_cubit


```

### constants
This folder contains all constants strings and end points related to the application
```
constants
├── constant
├── end_points

```

### data
This folder manages application data eg. retrieve data from the network, manage data cache
```
data
├── local
├── models
├── network
├── remote
```

### presentation
This folder presents data to a screen and handle user interactions
```
presentation
├── router
├── screens
├── styles
└── views
└── widgets

```
## Screenshots
![Screenshot 2022-08-28 121240](https://user-images.githubusercontent.com/46471716/194717452-320b7f6a-d285-4397-b8ab-c5decf22e7e2.png)
![Screenshot 2022-08-28 122219](https://user-images.githubusercontent.com/46471716/194717455-95c74766-c4a3-4520-b99f-7415a5a8a3fb.png)
![Screenshot 2022-08-28 122741](https://user-images.githubusercontent.com/46471716/194717459-52759d98-d24a-4014-9a23-8f067675850e.png)
![Screenshot 2022-08-28 124102](https://user-images.githubusercontent.com/46471716/194717460-acf1497a-faf6-4240-a9f5-18519fab4f5d.png)
![Screenshot 2022-08-28 124407](https://user-images.githubusercontent.com/46471716/194717462-6c4177c1-2c29-4ddd-8f71-48050c6f47e9.png)
![Screenshot 2022-08-28 180221](https://user-images.githubusercontent.com/46471716/194717464-058fa31e-2258-4421-8422-3fa2e4b55f39.png)
![Screenshot 2022-08-28 105930](https://user-images.githubusercontent.com/46471716/194717466-f4bf7737-717f-43ee-9479-7fbb2af2a89e.png)
![Screenshot 2022-08-28 111326](https://user-images.githubusercontent.com/46471716/194717468-2c657934-fb35-4442-9895-eeedbe93f4cf.png)
![Screenshot 2022-08-28 114806](https://user-images.githubusercontent.com/46471716/194717469-429e91af-8588-4cd3-8235-9b8e28a02c78.png)
![Screenshot 2022-08-28 120414](https://user-images.githubusercontent.com/46471716/194717470-3bd1b269-1dcb-44ff-85f4-0017801c7419.png)


## Google Play Store

https://play.google.com/store/apps/details?id=rody.pay
