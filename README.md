# apple-platforms

A convenient list of Apple platforms from [LLVM](https://github.com/llvm/llvm-project/blob/main/llvm/include/llvm/BinaryFormat/MachO.def#L123-L138).

## Example

### Run: `cargo run --example platform`

Output:

```shell
Platform { platform: "UNKNOWN", id: 0, name: "unknown", build_name: "unknown", target: "unknown", tapi_target: "unknown", marketing: "unknown" }
Platform { platform: "MACOS", id: 1, name: "macos", build_name: "macos", target: "macos", tapi_target: "macos", marketing: "macOS" }
Platform { platform: "IOS", id: 2, name: "ios", build_name: "ios", target: "ios", tapi_target: "ios", marketing: "iOS" }
Platform { platform: "TVOS", id: 3, name: "tvos", build_name: "tvos", target: "tvos", tapi_target: "tvos", marketing: "tvOS" }
Platform { platform: "WATCHOS", id: 4, name: "watchos", build_name: "watchos", target: "watchos", tapi_target: "watchos", marketing: "watchOS" }
Platform { platform: "BRIDGEOS", id: 5, name: "bridgeos", build_name: "bridgeos", target: "bridgeos", tapi_target: "bridgeos", marketing: "bridgeOS" }
Platform { platform: "MACCATALYST", id: 6, name: "macCatalyst", build_name: "macCatalyst", target: "ios-macabi", tapi_target: "ios-macabi", marketing: "macCatalyst" }
Platform { platform: "IOSSIMULATOR", id: 7, name: "iossimulator", build_name: "iossimulator", target: "ios-simulator", tapi_target: "ios-simulator", marketing: "iOS Simulator" }
Platform { platform: "TVOSSIMULATOR", id: 8, name: "tvossimulator", build_name: "tvossimulator", target: "tvos-simulator", tapi_target: "tvos-simulator", marketing: "tvOS Simulator" }
Platform { platform: "WATCHOSSIMULATOR", id: 9, name: "watchossimulator", build_name: "watchossimulator", target: "watchos-simulator", tapi_target: "watchos-simulator", marketing: "watchOS Simulator" }
Platform { platform: "DRIVERKIT", id: 10, name: "driverkit", build_name: "driverkit", target: "driverkit", tapi_target: "driverkit", marketing: "DriverKit" }
Platform { platform: "XROS", id: 11, name: "xros", build_name: "xros", target: "xros", tapi_target: "xros", marketing: "xrOS" }
Platform { platform: "XROS_SIMULATOR", id: 12, name: "xrsimulator", build_name: "xrsimulator", target: "xrsimulator", tapi_target: "xros-simulator", marketing: "Simulator" }
```

### Run: `cargo run --example triple`

Output:

```shell
Converted from aarch64-apple-visionos to arm64-apple-xros
```

## Authors

Copyright (c) 2024 Eugene Hauptmann

## License

[MIT](/LICENSE)