# PvPBot

**[Join the Discord](https://discord.gg/JmqmBGKz7z) to ask questions, get early access to the latest checkpoints, and try out the hosted server!**

A preview of the current state of the model... thanks to `6to7` for beta testing it:

<video src="https://github.com/user-attachments/assets/03ed276a-bd1e-436c-a622-d35f1452393f"></video>

PvPBot is a small Transformer-based model aimed at engaging in Minecraft PvP. It is trained from scratch with no human data involved (trained purely on self-play). The first version of the model has ~4 million parameters and takes the last 16 ticks into account.

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
