# Barter

> **Status:** Experimental
> This project was built as a concept and learning exercise. The implementation is still close to the Flutter starter app.

Flutter app concept for a gamified barter marketplace. The product idea combines goods and service exchange, avatars, reputation, rewards, and safer community trading.

## Summary

- [What it is](#what-it-is)
- [Goals](#goals)
- [Product concept](#product-concept)
- [Project map](#project-map)
- [Current state](#current-state)
- [Working notes](#working-notes)

## What it is

`barter` is a mobile app concept for people who want to trade goods or services without reducing every exchange to a cash sale. The intended product uses reputation, community features, and gamification to make barter safer and more engaging.

## Goals

- Explore a marketplace model centered on direct exchange.
- Make trust visible through reputation, ratings, verification, and trade history.
- Add progression through badges, levels, achievements, and avatar customization.
- Provide a foundation that can grow into marketplace listings, auctions, chat, and community features.

## Product concept

- Customizable user avatars.
- Gamified trade flow with points and rewards.
- Marketplace and auction-style listing surfaces.
- Reputation score based on completed trades and peer feedback.
- Community tools such as forums or chat rooms.
- Security concepts such as verification and fraud prevention.

## Project map

```text
barter/
├── lib/          # Flutter application entrypoint
├── android/      # Android shell
├── ios/          # iOS shell
├── macos/        # macOS shell
├── linux/        # Linux shell
├── windows/      # Windows shell
├── web/          # Web shell
└── pubspec.yaml
```

## Current state

The repository is still close to the default Flutter starter app. The README documents the product direction; the implementation has not caught up with the full marketplace concept yet.

## Working notes

- Treat `lib/main.dart` as starter code until the actual product shell replaces it.
- Update `pubspec.yaml` metadata before publishing or presenting the app externally.
- Keep marketplace, reputation, and reward behavior explicit in future domain models.
