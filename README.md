# FluCast

Open Source Podcast app for your Show

## Getting Started

Have you always wanted an exclusive app for your Podcast? Now you can customize and make available to your audience a player for Android and iOS developed with Flutter.

Simply configure your Podcast feed, tweak the app icon, build and make it available in stores.

## Main Features

FluCast has the most features that you need to play your show:

- [x] Podcast Cover
- [x] Podcast Description
- [x] Episodes Listing
- [x] Player Status
- [x] Play, Pause and Stop
- [x] 30 Seconds Seek
- [x] Episode Description

## Setting Up

Just change the `podcastFeedUrl` located on [feed.dart](https://github.com/luizeof/flucast_app/blob/master/lib/feed.dart) file.

You need to specify a valid **Podcast RSS Feed**.

```dart
final podcastFeedUrl = "https://anchor.fm/s/848f2e4/podcast/rss";
```

## Screens
Home | Episodes | Playing | Details
---- | ---- | ---- | ----
<img align="left" src="docs/home.png"> |  <img align="left" src="docs/episodes.png"> |  <img align="left" src="docs/playing.png"> |  <img align="left" src="docs/details.png">

## Dependencies

- flutter_launcher_icons (https://pub.dev/packages/flutter_launcher_icons)
- dart_pod (https://pub.dev/packages/dart_pod)
- html (https://pub.dev/packages/html)
- audioplayer (https://pub.dev/packages/audioplayer)

## Resources

- app icon (https://www.flaticon.com/free-icon/record_1064911)