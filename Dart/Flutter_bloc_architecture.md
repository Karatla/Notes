

```
lib/
├── app/
│   ├── app.dart
│   ├── router.dart
│   ├── app_bloc_observer.dart
│   └── di.dart                       // get_it dependency injection
│
├── core/
│   ├── constants/                    // global constants, colors, sizes
│   ├── error/                        // failures, exceptions
│   ├── utils/                        // helpers, formatters, extensions
│   ├── widgets/                      // shared reusable widgets
│   └── services/                     // global services (GPS, NFC, BLE, Camera…)
│
├── features/
│   ├── <feature_name>/
│   │   ├── data/
│   │   │   ├── models/               // DTOs (freezed/json_serializable)
│   │   │   ├── repositories/         // concrete impl
│   │   │   └── sources/
│   │   │       ├── remote/           // dio/retrofit APIs
│   │   │       └── local/            // hive/isar/secure_storage
│   │   ├── domain/
│   │   │   ├── entities/             // pure dart models
│   │   │   ├── repositories/         // abstract contracts
│   │   │   └── usecases/             // business logic
│   │   └── presentation/
│   │       ├── blocs/                // BLoC classes
│   │       └── pages/                // UI screens
│   │
│   ├── authentication/
│   ├── tracking/
│   ├── settings/
│   ├── profile/
│   └── more_features_here/
│
└── main.dart
```

