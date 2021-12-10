# Tronxy X5SA config
Tronxy X5SA Pro Klipper configuration

This is the actual `kliper_config` folder for my Tronxy X5SA Pro printer. The printer has been modded to use a [BigTreeTech Octopus Pro](https://amzn.to/3o0R3ZD) control board and [klipper](https://www.klipper3d.org) running on a [Raspberry Pi 4B](https://amzn.to/3HZat9d)

Please note that this is a living repo and the config files are constantly being updated based on either the mods I am doing to the machine or just because I have an idea. **Please do not** take it as is, your machine will probably vary, but feel free to get ideas and adapt to your needs.

You can find my posts on <https://marksmakerspace.com> and on Reddit as [u/SirThunderCloud](https://reddit.com/u/sirthundercloud)

## Mods and hardware changes

My mods to the machine include:
- [BigTreeTech Octopus Pro](https://amzn.to/3o0R3ZD)
- [TMC2209 Stepper drivers](https://amzn.to/319Q7tg)
- Dual independent Z axis stepper drivers
- LED light strip
- Magnetic steel flex plate with PEI and quick align stand

## Specific features & config

Config is divided in two folders, one for the hardware declarations and the other for all the macros. In these folders I tried to keep everything in small independent files to be able to find and modify everything easily.
