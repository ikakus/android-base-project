# Android Base Project

Based project armed using [Dagger2] (https://google.github.io/dagger/) for Dependency Injection and MVC architecture with Repository Pattern.
It has several managers classes that encapsulate features that are usually used in a project, most using inversion control to decouple the implementation.

The idea is that the project is to be able to cloned and serve directly to start a project without setting what is commonly used.

Developed by the [LateralView](https://lateralview.co) team.

### Include Libraries

- [Dagger2] (https://google.github.io/dagger/)
Compile-time dependency injection framework.
 
- [SimpleRESTClient] (https://github.com/julianfalcionelli/SimpleRESTClientHandler)
Open Source Android library that allows developers to easily make request to a REST server usign VOLLEY and GSON.

- [Glide] (https://github.com/bumptech/glide)
Fast and efficient open source media management and image loading framework.

- [Icepick] (https://github.com/frankiesardo/icepick)
Allows us via anotations save and restore instance state.

### Usefull Managers

- [Camera Manager] (https://github.com/LateralView/android-base-project/blob/master/app/src/main/java/co/lateralview/myapp/infraestructure/manager/CameraManager.java)

- [Internet Manager] (https://github.com/LateralView/android-base-project/blob/master/app/src/main/java/co/lateralview/myapp/infraestructure/manager/InternetManager.java)

- [Permissions Manager] (https://github.com/LateralView/android-base-project/blob/master/app/src/main/java/co/lateralview/myapp/infraestructure/manager/PermissionsManager.java)

- [System Manager] (https://github.com/LateralView/android-base-project/blob/master/app/src/main/java/co/lateralview/myapp/infraestructure/manager/SystemManager.java)

- [Social Manager] (https://github.com/LateralView/android-base-project/blob/master/app/src/main/java/co/lateralview/myapp/infraestructure/manager/SocialManager.java)

- [File Manager] (https://github.com/LateralView/android-base-project/blob/master/app/src/main/java/co/lateralview/myapp/infraestructure/manager/interfaces/FileManager.java)

- [Image Manager] (https://github.com/LateralView/android-base-project/blob/master/app/src/main/java/co/lateralview/myapp/infraestructure/manager/interfaces/ImageManager.java)

- [Parser Manager] (https://github.com/LateralView/android-base-project/blob/master/app/src/main/java/co/lateralview/myapp/infraestructure/manager/interfaces/ParserManager.java)

- [Shared Preferences Manager] (https://github.com/LateralView/android-base-project/blob/master/app/src/main/java/co/lateralview/myapp/infraestructure/manager/interfaces/SharedPreferencesManager.java)

- [Task Manager] (https://github.com/LateralView/android-base-project/blob/master/app/src/main/java/co/lateralview/myapp/infraestructure/manager/interfaces/TaskManager.java)

### Package Structure

```
android-base-project/app/src/main/java/co/lateralview/myapp/
└───application
│   │   ...
└───domain
│   └─── model
│   │    │   ...
│   └─── repository
│        └─── implementation
│        └─── interfaces
│        │   ...
└───infraestructure
│   └─── manager
│   │    └─── implementation
│   │    └─── interfaces
│   │    │   ...
│   └─── networking
│   │    └─── implementation
│   │    └─── interfaces
│   │    │   ...
│   └─── pushNotification
│        │   ...
└───ui
    └─── activity
    │    │   ...
    └─── broadcast
    │    │   ...
    └─── common
    │    │   ...
    └─── fragment
    │    │   ...
    └─── util
         │   ...
```

If you are going to be a big application UI recommend that packages are created for each functionality (screen).

### Extra

[Here] (https://github.com/LateralView/android-lateral-skeleton/wiki) you will find all the documentation related to Android Lateral naming standards, good practices, tips, useful libraries and more!

For any suggestions or if you want to join our team please contact us via [android@lateralview.net](mailto: android@lateralview.net)
