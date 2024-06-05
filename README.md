# react-native-sync-storage

A synchronous, unencrypted, persistent, key-value storage system for React Native.

## Underlying native code
- On iOS, this uses `UserDefaults` to store key-value pairs.
- On Android, this uses `SharedPreferences`to store key-value pairs.
