# Contributing to Japanese Swordsmith

First of all, thank you for your interest in contributing to **Japanese Swordsmith**!

Whether you are fixing bugs, improving documentation, translating the mod, creating artwork, or suggesting new ideas, every contribution is appreciated.

Our goal is to build a realistic and enjoyable Japanese swordsmithing experience together with the community.

---

# Code of Conduct

Please be respectful and constructive.

We welcome contributors from all backgrounds and experience levels.

Harassment, discrimination, or toxic behavior will not be tolerated.

---

# Before You Start

Please check the following before opening an Issue or Pull Request:

* Search existing Issues to avoid duplicates.
* Read the project documentation.
* Make sure your idea fits the project's design philosophy.
* For major features, open a Discussion or Issue first before starting implementation.

---

# Development Environment

Current Target

* Minecraft Forge 1.20.1
* Java 17

Recommended IDE

* IntelliJ IDEA
* Eclipse

Git is required.

---

# Branch Strategy

Please do **not** work directly on the `main` branch.

Create a feature branch instead.

Examples:

```text
feature/tatara
feature/forging
feature/gui
feature/create-integration
feature/slashblade
fix/quenching-bug
docs/readme-update
```

---

# Pull Requests

A Pull Request should focus on **one feature or one fix only**.

Please include:

* A short description
* Why the change is needed
* Screenshots (if UI changes)
* Testing information

Large unrelated changes may be requested to be split into multiple Pull Requests.

---

# Coding Style

Please follow these guidelines:

* Use meaningful class names.
* One class should have one clear responsibility.
* Keep methods small and readable.
* Avoid duplicated code.
* Write comments only when explaining **why**, not **what**.

Use UpperCamelCase for classes.

Example:

```java
TataraFurnaceBlock
ForgeScreen
BladeData
```

Use lower_snake_case for resource IDs.

Example:

```text
tatara_furnace
unfinished_blade
polishing_table
certificate_paper
```

---

# Project Structure

```text
com.jss.japaneseswordsmith

block/
blockentity/
item/
menu/
screen/
recipe/
registry/
smithing/
integration/
client/
util/
```

Please place new classes in the appropriate package.

---

# JSON Formatting

Use:

* 4-space indentation
* Consistent key ordering
* No unnecessary whitespace

Example:

```json
{
    "type": "jss:forging",
    "ingredient": {
        "item": "jss:tamahagane"
    },
    "result": {
        "item": "jss:unfinished_blade"
    }
}
```

---

# Assets

Default texture resolution:

* 32×32

Please keep a consistent visual style.

Supported asset contributions:

* Textures
* Models
* Sounds
* GUI artwork
* Icons

---

# Localization

Translations are always welcome.

Current languages:

* English (Primary)
* Japanese

Future languages may include:

* Chinese
* Korean
* German
* French
* Spanish

Please keep translations natural rather than literal whenever possible.

---

# Documentation

Documentation improvements are highly appreciated.

Examples:

* Tutorials
* API documentation
* Game mechanics
* Research sources
* Diagrams

---

# Bug Reports

A good bug report should include:

* Minecraft version
* Forge version
* Mod version
* Installed mods
* Steps to reproduce
* Expected behavior
* Actual behavior
* Crash log (if applicable)

---

# Feature Requests

When suggesting a feature, please explain:

* What problem it solves
* Why it fits the project
* How it affects gameplay
* Whether it impacts multiplayer
* Whether it affects SlashBlade compatibility

Historical references are always appreciated when suggesting traditional swordsmithing features.

---

# Addons

Community addons are encouraged.

Addon developers may:

* Add new swords
* Add new materials
* Add new forging mechanics
* Add integrations with other mods

Please avoid modifying the core mod whenever possible.

Instead, use the provided API and data-driven systems.

---

# Integrations

Official integrations currently include:

* SlashBlade (Required)
* JEI
* EMI
* Create
* Jade
* Patchouli

Additional integrations are welcome if they align with the project's goals.

---

# Design Philosophy

When contributing, please keep these principles in mind.

* Realistic, but enjoyable
* Learn through gameplay
* Multiplayer-friendly
* Data-driven design
* Performance-conscious
* Extensible architecture

If a feature improves realism but significantly reduces gameplay enjoyment, gameplay should take priority.

---

# Need Help?

If you have questions, feel free to:

* Open a GitHub Discussion
* Open an Issue
* Ask the community

We are happy to help new contributors.

---

Thank you for helping make **Japanese Swordsmith** better for everyone!
