# ModDecompilerTool
ModDecompilerTool is a tool to decompile Minecraft mods using the CFR decompiler and apply mappings from a mappings directory to make the decompiled code more readable.

# Usage
To use ModDecompilerTool, simply download the .jar file and run the following command in a terminal:
`java -jar ModDecompilerTool.jar /path/to/mymod.jar /path/to/output/dir /path/to/mappings/dir`

Please note that the mappings directory should only contain the mapping files for the version of the mod being decompiled (params.txt, methods.txt, and fields.txt) in the format func_1234 isRaining().

# Disclaimer
ModDecompilerTool is not endorsed by or affiliated with Mojang or Minecraft. Use at your own risk.
