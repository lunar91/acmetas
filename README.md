# LuNaR's Asheron's Call vTank Metas

A Collection of Asheron's Call vTank metas. These metas are built with [METAF](github.com/JJEII/metaf).

## Usage
Download the metas and/or navs that you want from the `dist/` folder. Add these to your VirindiTank folder. Usage instructions for each meta can be found in the corresponding `MetaName_README.md` file.


# Contributing
Feel free to submit a Pull request with your changes / additions.

- **Automatic Building with VSCode**
  - Dependencies
    - MetaF directory added to %PATH%
    - VSCode RunOnSave extension
  - `.vscode/settings.json` includes configuration for automatically building src to dist.
    - You can add automatically building/overwriting your meta in your vTank folder by updating the `"cmd"` line of settings.json to include `; metaf ${file} C:\\\\Games\\\\VirindiPlugins\\\\VirindiTank\\\\` at the end. Make sure to update the path (escaped) to match your vTank install path.

