# Flame realtime shooting game with Supabase

#### Guide: [How to build a real-time multiplayer game with Flutter Flame](https://supabase.com/blog/flutter-real-time-multiplayer-game)

### Demo
https://github.com/khlebobul/flame_realtime_shooting/assets/77191581/2fb9f08d-03ca-40b9-be9e-2eaf9891dd91

### [Run flutter app on multiple devices](https://www.youtube.com/watch?v=-35E-oCXDUs)

My launch.json ⬇️

```json
{
    "version": "0.2.0",
    "configurations": [
        {
            "name": "flame_realtime_shooting",
            "request": "launch",
            "type": "dart"
        },
        {
            "name": "Chrome",
            "request": "launch",
            "type": "dart",
            "deviceId": "chrome",
        },
        {
            "name": "ios",
            "request": "launch",
            "type": "dart",
            "deviceId": "your device id",
        },
        {
            "name": "flame_realtime_shooting (release mode)",
            "request": "launch",
            "type": "dart",
            "flutterMode": "release"
        }
    ],
    "compounds": [
        {
            "name": "All Devices",
            "configurations": ["ios", "Chrome"]
        }
    ]
}
```




