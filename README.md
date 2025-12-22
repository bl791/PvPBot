# PvPBot

Can RL be used to teach AI PvP Minecraft?

**Features:**

- Sword PvP
- Shield usage
- Pathfinding (learned by the model, not using an algorithm)

Training is conducted in a custom headless RL environment. Parts of this environment are released through the [pyzalea](https://github.com/bl791/pyzalea) library, bindings of [azalea](https://github.com/azalea-rs/azalea) to Python. By using a headless Rust client rather than the native Java client, the performance is significantly improved.

## Get Started

**Inference code will be released soon.**

## Models

The checkpoints are made publicly available on [Hugging Face](https://huggingface.co/bl791/mc-pvp-rl).

## License

The code is licensed under the LGPL-2.1 license. All model checkpoints are licensed under the CC-BY-NC-4.0 license.
