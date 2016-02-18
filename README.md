# Spartan's Core
The objective of Spartan's Core (SCMod) is to provide a standarization for the Minecraft Forge that Forge itself does not provide. It is meant to extend beyond Forge, and to enable version ambigiouation, or the ability to ignore the version, and develop for any version. Instead of forcing the mod developer to develop for different versions using different branches, when this coremod is used, the version of Minecraft shall be irrelevant, and instead will be handled by the specific library version.

# Plans
- Standarize commonly created Mod Methods and Classes
- Improve Minecraft and Forge Modifcation interaction
- Support 1.7.10, 1.8, 1.8.9, and eventually 1.9, without requiring more then one file for other mods (a specific version for this coremod will be required)
- Opaque Version Wrapping, interaction with Minecraft versions is entirely ambigious
- Download Manager, shall search for new mod versions (if given) and will install if available (if option is on), however requires restart, options for auto-shutdown.