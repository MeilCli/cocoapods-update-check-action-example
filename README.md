# cocoapods-update-check-action-example
example and test repository.

`pod outdated`:
```
Updating spec repo `trunk`
Analyzing dependencies
The color indicates what happens when you run `pod update`
<green>	 - Will be updated to the newest version
<blue>	 - Will be updated, but not to the newest version because of specified version in Podfile
<red>	 - Will not be updated because of specified version in Podfile

The following pod updates are available:
- RxCocoa 4.5.0 -> 5.0.0 (latest version 5.0.0)
- RxSwift 4.5.0 -> 5.0.0 (latest version 5.0.0)

[!] Automatically assigning platform `iOS` with version `12.2` on target `cocoapods-update-check-action-example` because no platform was specified. Please specify a platform for this target in your Podfile. See `https://guides.cocoapods.org/syntax/podfile.html#platform`.
```