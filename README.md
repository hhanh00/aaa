```
flutter_rust_bridge_codegen create --org org.hanh --rust-crate-name laaa aaa
```

- Create github project
- Setup repository secrets
- R/W Workflow permissions
- release-please (manifest, config)
- flutter_launcher_icon
- distribute_options

## Android
- Generate android keystore
`keytool -genkey -v -keystore aaa-keystore.jks -keyalg RSA -keysize 2048 -validity 10000 -alias aaa`
- Update `build.gradle.kts`
- Update `ndk` 27.0.12077973
- [Fix Flutter plugin bug](https://github.com/irondash/cargokit/issues/93)

## IOS
- Export Apple Distribution Key
- Create new Provisioning Profile for app store
- Copy export_options.plist

## Linux/Windows
- packaging

## MacOS
- Enable automatic signing & local deployment
- app.json
