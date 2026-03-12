Zaptastic
=======

Retro-style top-down shooter built with SpriteKit and Swift.

Overview
--------
Zaptastic is a small iOS arcade shooter example project demonstrating SpriteKit usage, simple enemy wave configuration via JSON, and particle effects. It's intended as a learning/example project rather than a full commercial game.

Highlights
- Built with Swift and SpriteKit
- Data-driven enemy/wave configuration using JSON (`enemy-types.json`, `waves.json`)
- Easy to extend with new enemy types and waves

Requirements
- macOS with Xcode (open the included Xcode project)
- Xcode that supports Swift 5 (project is configured with Swift 5.0)
- iOS deployment target: 18.5 (see Xcode project settings)

Quick start (build & run)
1. Open the Xcode project: `Zaptastic/Zaptastic.xcodeproj` in Xcode
2. Select the `Zaptastic` scheme and a Simulator or device
3. If code signing prompts appear, open the target's Signing & Capabilities and select your Development Team
4. Build (⌘B) and run (⌘R)

Project structure
- Zaptastic/ - Xcode project and source
  - GameScene.swift, GameViewController.swift, EnemyNode.swift, etc.
  - `enemy-types.json`, `waves.json` — JSON files used to configure enemies and waves
  - Assets.xcassets/ — image assets and sprite atlases

Configuration
- Add or change enemy types in `enemy-types.json` (see `EnemyType.swift` for fields)
- Edit `waves.json` to change the sequence/behaviour of enemy waves

Suggested GitHub description and topics
- Description: "Retro-style SpriteKit top-down shooter built in Swift (iOS)."
- Topics: swift, spritekit, game, arcade, ios, indie-game, 2d

Contributing
- Feel free to open issues or pull requests. Keep changes small and focused.

License
- No license file is included by default. If you want an open-source license, consider adding an `LICENSE` file (MIT/Apache-2.0/etc.).

Contact
- Maintainer: George Clinkscales (see repo metadata or commit history)
