# IconsX Plus

[![pub.dev](https://img.shields.io/pub/v/iconsx_plus?label=pub.dev&logo=dart)](https://pub.dev/packages/iconsx_plus)
[![GitHub](https://img.shields.io/badge/mayurpitroda-GitHub-black?logo=github)](https://github.com/mayurpitroda)
[![Issues](https://img.shields.io/github/issues/mayurpitroda/iconsx_plus)](https://github.com/mayurpitroda/iconsx_plus/issues)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/mayurpitroda/iconsx_plus/blob/main/LICENSE)

**IconsX Plus** is a Flutter package that provides a rich collection of popular icon packs in one place. Quickly find and add beautiful icons to your app with a simple, consistent API — and full support for the latest Flutter versions.

## Installation

Add to your `pubspec.yaml`:

```yaml
dependencies:
  iconsx_plus: ^1.0.0
```

Then import:

```dart
import 'package:iconsx_plus/iconsx_plus.dart';
```

## Icon Sets

| # | Icon Set | Version |
|---|----------|---------|
| 1 | [AntDesign](#1-antdesign) | 5.12.2 |
| 2 | [Bootstrap](#2-bootstrap) | 1.11.2 |
| 3 | [BoxIcons](#3-boxicons) | 2.1.4 |
| 4 | [Brands Logo](#4-brands) | — |
| 5 | [Clarity](#5-clarity) | 12 |
| 6 | [EvaIcons](#6-evaicons) | 1.1.3 |
| 7 | [Flags Logo](#7-flag) | — |
| 8 | [FontAwesome](#8-fontawesome) | 6.5.1 |
| 9 | [HeroIcons](#9-heroicons) | 2.0.18 |
| 10 | [Iconsax](#10-iconsax) | 1.0 |
| 11 | [IonIcons](#11-ionicons) | 7.1.0 |
| 12 | [LineAwesome](#12-lineawesome) | 1.3.1 |
| 13 | [MingCute](#13-mingcute) | 2.89 |
| 14 | [OctIcons](#14-octicons) | 19.8.0 |
| 15 | [PixelArtIcons](#15-pixelarticons) | 1.8 |
| 16 | [TeenyIcons](#16-teenyicons) | latest |
| 17 | [ZondIcons](#17-zondicons) | latest |

## 1. AntDesign

AntDesign provides three types of icons: Fill, Outline, and TwoTone icons. Append `_fill`, `_outline`, or `_twotone` as a suffix.

```dart
Icon(AntDesign.gitlab_fill),
Icon(AntDesign.sketch_outline),
Icon(AntDesign.environment_twotone),
```

## 2. Bootstrap

Bootstrap offers Outline and Fill icons. Add `_fill` suffix for filled variants.

```dart
Icon(Bootstrap.google),
Icon(Bootstrap.bootstrap),
Icon(Bootstrap.github),
```

## 3. BoxIcons

BoxIcons provides Regular (`bx_`), Solid (`bxs_`), and Logo (`bxl_`) icons.

```dart
Icon(BoxIcons.bxl_apple),
Icon(BoxIcons.bx_git_branch),
Icon(BoxIcons.bxs_cookie),
```

## 4. Brands

```dart
Brand(Brands.icons8),
Brand(Brands.android_studio),
```

## 5. Clarity

Clarity provides Outline, Solid, and Line icons via `_outline`, `_solid`, and `_line` suffixes.

```dart
Icon(Clarity.map_outline_badged),
Icon(Clarity.application_solid),
Icon(Clarity.camera_line),
```

## 6. EvaIcons

EvaIcons offers Outline and Fill icons. Add `_outline` for outlined variants.

```dart
Icon(EvaIcons.clipboard),
Icon(EvaIcons.flash),
Icon(EvaIcons.clipboard_outline),
```

## 7. Flag

```dart
Flag(Flags.india),
Flag(Flags.united_kingdom),
Flag(Flags.united_states_of_america),
```

## 8. FontAwesome

FontAwesome provides Regular, Solid (`_solid`), and Brand (`_brand`) icons.

```dart
Icon(FontAwesome.stripe_brand),
Icon(FontAwesome.folder_open),
Icon(FontAwesome.bug_solid),
```

## 9. HeroIcons

```dart
Icon(HeroIcons.printer),
Icon(HeroIcons.pencil_square),
Icon(HeroIcons.play_circle),
```

## 10. Iconsax

Iconsax provides Bold (`_bold`), Bulk (`_bulk`), and Outline (`_outline`) icons.

```dart
Icon(Iconsax.cake_bold),
Icon(Iconsax.clock_bulk),
Icon(Iconsax.dollar_circle_outline),
```

## 11. IonIcons

```dart
Icon(IonIcons.bug),
Icon(IonIcons.finger_print),
Icon(IonIcons.logo_react),
```

## 12. LineAwesome

```dart
Icon(LineAwesome.amazon),
Icon(LineAwesome.birthday_cake_solid),
Icon(LineAwesome.cc_visa),
```

## 13. MingCute

```dart
Icon(MingCute.knife_line),
Icon(MingCute.badminton_line),
Icon(MingCute.currency_bitcoin_fill),
```

## 14. OctIcons

```dart
Icon(OctIcons.code_of_conduct),
Icon(OctIcons.copilot),
Icon(OctIcons.verified),
```

## 15. PixelArtIcons

```dart
Icon(PixelArtIcons.gif),
Icon(PixelArtIcons.human),
Icon(PixelArtIcons.heart),
```

## 16. TeenyIcons

```dart
Icon(TeenyIcons.google_play_store),
Icon(TeenyIcons.heart),
Icon(TeenyIcons.android),
```

## 17. ZondIcons

```dart
Icon(ZondIcons.shield),
Icon(ZondIcons.trophy),
Icon(ZondIcons.coffee),
```

## License

MIT License © [Mayur Pitroda](https://github.com/mayurpitroda)

---

## Credits

This package is a maintained fork of [icons_plus](https://github.com/chouhan-rahul/icons_plus) originally created by [Rahul Chouhan](https://github.com/chouhan-rahul). All icon assets and original package structure are credited to the original author. This fork adds Flutter 3.44+ compatibility and continued maintenance under the `iconsx_plus` package name.
