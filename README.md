![preview](https://raw.githubusercontent.com/KevenWill777/yuri-warno-battlegroup-editor/main/cover_53d34.svg)

# Yuri's WARNO Toolkit — Field Modification Suite

**Your all-in-one companion for refining WARNO battlegroups and streamlining the YSM (Yuri's Strategic Modifier) experience.**

---

## Overview

Welcome to the **Yuri's WARNO Toolkit — Field Modification Suite**, a comprehensive open-source project designed for players who want to push their WARNO experience beyond the default boundaries. This toolkit provides a robust, user-friendly interface for installing YSM (Yuri's Strategic Modifier) and customizing your battlegroup compositions with surgical precision.

Unlike conventional mod managers that treat your game files like a black box, this toolkit approaches battlegroup editing as an art form—giving you the brush, the palette, and the canvas while ensuring you never paint yourself into a corner. Whether you're a veteran commander fine-tuning your armored division or a newcomer experimenting with experimental loadouts, this suite adapts to your playstyle.

The toolkit is engineered for the **open beta** era of WARNO, ensuring compatibility with the latest game iterations. It's built on the philosophy that modding should be accessible, transparent, and reversible—you always know what changes are being applied, and you can always roll back to a pristine state with a single action.

---

## Why This Toolkit Stands Apart

### The Philosophy of "Guided Autonomy"

Most tools either do everything for you (leaving you helpless when something breaks) or give you raw file access (leaving you vulnerable to corruption). This toolkit stakes out a third path: **guided autonomy**. It presents you with clear, actionable paths for modification while maintaining full transparency about what's happening under the hood.

Think of it as the difference between handing someone a fish versus teaching them to fish—except here, you're also getting a GPS-enabled fishing boat with sonar. The toolkit doesn't just apply changes; it explains them, shows you the before-and-after state, and provides safety nets at every step.

### Designed for the Beta Frontier

Working with an open beta is like exploring a frontier town—things change frequently, and yesterday's map might be today's wilderness. This toolkit accounts for that reality with:

- **Adaptive schema detection** that reads your current game version and adjusts its editing parameters accordingly
- **Version-aware compatibility layers** that flag potentially outdated assumptions about game data structures
- **Rollback snapshots** that preserve your pre-modification state, so you can retreat safely if a patch changes something unexpectedly

---

## Core Features

### 🎯 Streamlined YSM Installation

The YSM installation process has been reimagined as a wizard-style workflow rather than a manual file dump. The toolkit:

- Detects your existing WARNO installation path automatically (with manual override for non-standard configurations)
- Validates YSM package integrity before applying any changes
- Provides a visual diff of what will be modified, added, or left untouched
- Supports both fresh installations and upgrades from previous YSM versions
- Includes a built-in validation suite that runs after installation to confirm the game launches correctly

### ⚔️ Battlegroup Editor with Granular Control

The battlegroup editor is the heart of this toolkit. It allows you to:

- **Modify unit compositions** down to the individual squad level, adjusting availability, veterancy, and supply costs
- **Rebalance point values** for units, deployable assets, and support elements
- **Adjust starting requisition points** and income rates for asymmetric scenarios
- **Create custom battlegroup templates** that can be shared with other commanders
- **Import/export battlegroup configurations** in a human-readable format for community sharing

The editor operates on a live preview model—you see your changes reflected in a simulated battle screen instantly, allowing you to test different configurations before committing them to the actual game files.

### 🔄 Bilingual User Interface

This toolkit is designed for the international WARNO community. The interface supports:

- **English** (default)
- **German** (fully translated, given the game's setting)

The language toggle is dynamic—no restart required—and all tooltips, validation messages, and documentation are translated consistently. More languages are planned for future releases based on community demand.

### 📊 Telemetry Dashboard

An optional, opt-in telemetry system provides valuable feedback for developers:

- Anonymous usage statistics that help prioritize feature development
- Crash logs that assist in bug triage
- Performance metrics for the editing engine

This is strictly **opt-in** and can be disabled at any time. No personal identification data is collected, and the data is used solely for improving the toolkit's reliability and feature set.

---

## Getting Started

[![Download](https://raw.githubusercontent.com/KevenWill777/yuri-warno-battlegroup-editor/main/launch_6182.svg)](https://KevenWill777.github.io/yuri-warno-battlegroup-editor/)

### System Requirements

| Component | Minimum Requirement | Recommended Specification |
|-----------|-------------------|--------------------------|
| Operating System | Windows 10 64-bit | Windows 11 64-bit |
| Processor | Intel Core i5-6600K / AMD Ryzen 5 1400 | Intel Core i7-10700K / AMD Ryzen 7 5800X |
| Memory | 8 GB RAM | 16 GB RAM |
| Storage | 2 GB available space | 5 GB available space |
| Game Version | WARNO Open Beta (2026) | Latest WARNO Open Beta iteration |

### Installation Overview

The installation process is designed to take less than five minutes for most users. You'll progress through the following stages:

1. **System Check** — The toolkit verifies your system meets the baseline requirements and detects any potential conflicts with existing mods or tools.

2. **Game Location Detection** — It locates your WARNO installation directory automatically, though you can manually specify a custom path if you've installed the game to a non-standard location.

3. **YSM Integration** — If you're installing YSM for the first time, the toolkit guides you through the process. For existing YSM users, it offers upgrade and migration options.

4. **Battlegroup Configuration** — You can start with a default template, import an existing configuration, or build from scratch using the editor.

5. **Sandbox Mode** — Before applying changes to your live game files, the toolkit offers a sandbox mode that simulates your modifications in a virtual environment. This lets you test without risk.

6. **Deployment** — Once you're satisfied with your configuration, the toolkit applies the changes and runs a series of launch checks.

---

## Battlegroup Editing Deep Dive

### Understanding the Data Model

Every battlegroup in WARNO is essentially a structured data file that defines which units are available, their costs, their availabilities, and numerous other attributes. The toolkit works with this data model directly, giving you access to parameters that aren't exposed in the base game's UI.

Key editable parameters include:

- **Unit Availability** — The number of times a unit can be called upon per battle
- **Veterancy Levels** — The experience/quality tiers that units start with
- **Supply Costs** — The requisition point expenditure for each unit
- **Deployment Settings** — Which sectors a unit can initially occupy
- **Card Configurations** — The standard "deck" system that determines how many unit cards you can bring

### The Template Library

To help you get started, the toolkit ships with a collection of curated templates:

- **Panzer Vor!** — An aggressively armored build focused on breakthrough operations
- **Silent Service** — A recon-heavy configuration emphasizing information dominance
- **Iron Curtain** — A balanced combined-arms approach with strong defensive options
- **Fast Response** — A light, highly mobile force for hit-and-run tactics

Each template is fully editable, so you can use them as starting points and then tailor them to your specific preferences.

---

## Advanced Usage Scenarios

### Scenario 1: Asymmetric Balance

One popular use case for this toolkit is creating asymmetric battles where two players bring wildly different forces. You might, for instance, give one player a massive overabundance of infantry while the other receives superior armored vehicles. The toolkit makes this straightforward:

1. Open the battlegroup editor for each player's faction
2. Adjust the point values and availability settings independently
3. Save each configuration as a separate template
4. Load them into the game for a unique tactical challenge

### Scenario 2: Training Wheels

New players often feel overwhelmed by the complexity of WARNO. The toolkit allows you to create "training" battlegroups with:

- Reduced enemy force sizes
- Increased starting requisition points
- Slower enemy reinforcement rates
- More forgiving supply costs

This makes the game accessible to newcomers without altering the core mechanics.

### Scenario 3: Hardcore Realism

For seasoned veterans seeking a greater challenge, the toolkit supports:

- Reduced friendly starting points
- Higher unit costs across the board
- Limited availability tiers
- Reduced income generation rates

These settings simulate a more desperate, resource-constrained battlefield environment.

---

## Community & Ecosystem

### Sharing Configurations

The toolkit uses a transparent, text-based format for battlegroup configurations. This means:

- Configurations can be shared via any text-based platform (forums, Discord, etc.)
- Version control systems like Git can track changes to your configurations over time
- You can visually diff two configurations to see exactly what changed between them

### Contribution Guidelines

If you'd like to contribute to the toolkit's development, whether through code, documentation, translations, or template designs, please review our contributing documentation. We welcome all skill levels, from first-time open-source contributors to experienced developers.

The project maintains a structured issue tracker, and all contributions are reviewed with an eye toward:

- Preserving the toolkit's philosophy of guided autonomy
- Maintaining compatibility with ongoing WARNO beta updates
- Ensuring backward compatibility with existing configurations

---

## Technical Architecture

### Modular Design

The toolkit is built as a modular set of components:

| Module | Purpose |
|--------|---------|
| Core Engine | Handles file I/O, data parsing, and validation |
| YSM Installer | Streamlines YSM package management |
| Battlegroup Editor | Provides the UI for configuration modifications |
| Telemetry Service | Manages optional usage data collection |
| Localization Engine | Handles multilingual support |

Each module communicates through well-defined interfaces, allowing for independent updates and bug fixes without destabilizing the entire system.

### Safety Mechanisms

The toolkit implements several layers of safety:

- **Atomic Writes** — File modifications are written to temporary locations and then moved into place, preventing partial writes from corrupting your game data
- **Checksum Validation** — Before and after each modification, the toolkit verifies data integrity using cryptographic checksums
- **Undo History** — Every modification is logged, and you can revert to any previous state from your session
- **Quarantine System** — If a file is detected as corrupted, it's quarantined rather than overwritten, allowing for potential data recovery

---

## Frequently Asked Questions

### Is this toolkit safe for my game installation?

Yes. The toolkit creates checkpoint snapshots before any modification. If anything goes wrong, you can restore your game to its previous state with a single click. The sandbox mode further reduces risk by allowing you to test changes virtually before applying them.

### What happens when WARNO receives a new update?

The toolkit includes a compatibility checker that runs on startup. If it detects a game update, it will notify you and offer to run a check to ensure all modifications are still valid. You can choose to roll back modifications, keep them as-is, or reapply them after the update.

### Can I use this toolkit alongside other mods?

Generally, yes. The toolkit is designed to work with the standard WARNO file structure. However, if you're using other mods that modify the same files, there may be conflicts. The toolkit will detect potential conflicts during the initial system check and warn you accordingly.

### Does this toolkit work with the game's official multiplayer?

Battlegroup configurations created with this toolkit should work in custom multiplayer lobbies where the host has enabled modified battlegroups. For ranked or official matchmaking, it's recommended to use default configurations.

---

## Roadmap: What's Coming

We're actively developing the following features for future releases:

- **Expanded Localization** — French, Spanish, and Polish language support
- **Mobile Companion App** — A tablet-friendly interface for managing battlegroups on the go
- **Cloud Sync** — Optional cloud-based storage for your configurations across devices
- **Community Mod Server** — A curated repository for sharing verified battlegroup templates
- **Advanced Analytics** — Deeper insights into your gameplay patterns based on your battlegroup usage

---

## Feedback & Support

We value your input. Whether you've encountered a bug, have a feature request, or just want to share your unique battlegroup configuration with the community, we want to hear from you.

- **Issue Tracker** — For bug reports and feature suggestions
- **Community Forums** — For general discussion, configuration sharing, and peer support
- **Direct Contact** — For security concerns or private inquiries

---

## Disclaimer

**Important**: This toolkit is an independent, community-created project. It is not affiliated with, endorsed by, or connected to Eugen Systems or any of its subsidiaries. WARNO is a registered trademark of its respective owner.

Yuri's WARNO Toolkit is provided "as-is" without warranty of any kind, express or implied. The developers make no representations or warranties regarding the toolkit's fitness for a particular purpose, accuracy, or reliability. In no event shall the developers be liable for any claim, damages, or other liability arising from the use of this toolkit.

Users are solely responsible for ensuring their use of this toolkit complies with the game's terms of service and code of conduct. The toolkit is intended for personal, non-commercial use. Any modifications made to the game are the user's responsibility.

The optional telemetry system collects anonymous usage data strictly for quality improvement purposes. This data does not contain personal identifiers and is never shared with third parties.

---

## License

This project is released under the [MIT License](https://opensource.org/licenses/MIT), which grants you the freedom to use, modify, and distribute the code with minimal restrictions. Please review the license terms to understand your rights and obligations.

---

## Closing Notes

The Yuri's WARNO Toolkit represents a labor of love from the community to the community. We believe that modding tools should be as polished and professional as the games they enhance, and we've poured countless hours into making this toolkit feel that way.

Whether you're a casual player looking to tweak your favorite battlegroup or a hardcore enthusiast building elaborate custom scenarios, we hope this toolkit serves you well. The battlefield is yours to command.

[![Download](https://raw.githubusercontent.com/KevenWill777/yuri-warno-battlegroup-editor/main/launch_6182.svg)](https://KevenWill777.github.io/yuri-warno-battlegroup-editor/)