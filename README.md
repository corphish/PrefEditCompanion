# PrefEdit Companion #

PrefEdit Companion is a companion app for PrefEdit. PrefEdit uses this app to perform Shared Preference related operations. There is detailed F.A.Q within the app. You can find app downloads in the downloads section under tags.

### Package name

Package name is `com.booo.prefs`. This is an official product from the developers of PrefEdit, for PrefEdit.

### Version history ###

| Version Name | Version Code | Release date |
|--------------|--------------|--------------|
| 1.0 | 1 | 2021-06-14 |
| 1.0.1 | 2 | 2021-06-16 |

### Compatibility with PrefEdit ###

PrefEdit will expect the following companion app version so that it can work. Idea is to have it backward compatible (new versions of PrefEdit should be able to work with old versions of companion, as PrefEdit will be the one that will be updated most frequently).

| PrefEdit app version code | Minimum required companion app version code | Notes |
|---------------------------|---------------------------------------------|-------|
| 46 | 1 | Initial support for companion is introduced in version code `46` of PrefEdit. PrefEdit versions below 46 will not be able to work with the companion. |
| 47 | 2 | Companion app with version code 2 add supports for chunked data transmission, and PrefEdit with version code 47 can make use of the chunked data transmission abilities. Really not recommended to use with companion version 1, although it can still make use of it. |