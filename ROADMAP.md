# TootSDK Road map 🗺️

All good things take time to build.
We figured that it was best to release TootSDK at a base level of operation  and then keep enhancing from there.

If you see anything in our future road map that is particularly important to you, then we encourage you to look at our [contribution guide](./CONTRIBUTING.md) and submit us a PR! 🤝

## Version 0.1 ✅
- Authorization calls and ability to return the access token to the parent app for safe storage in the keychain etc
- All status calls
    - Publishing, Editing, Deleting
    - Mute/unmute conversations
    - Pin/Unpin posts
    - Boosting, Favouriting, Bookmarking
    - Get parent and child statuses in context
    - See who boosted a status
- Ability to have more than one TootClient connected to more than one instance
- Async Sequences for timelines and statuses
- Example SwiftUI app showing all major operations completed so far

## Immediate next steps:

- Opt in to other timeline types 
- Lists
- Blocking/muting/privacy operations
- Convenience function to detect application behaviours such as editing posts
- AppKit example

## Beyond ... 🔮
- Account operations
- Extended support for other Fediverse server types and their specific operations
    e.g:
    - PixelFed
    - Pleroma
    - MissKey
