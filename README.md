# OneLoader for Mac
OneLoader port for the OMORI Apple Silicon Patch.

This is a fork of OneLoader that patches newer versions of OneLoader in the same way done for 77Loader.

# Instructions
The installation process is the same as the one for vanilla OneLoader.

1) Download your copy of OMORI from Steam. Make sure you have launched OMORI at least once.
2) Download and run the script from [this repository](https://github.com/SnowpMakes/omori-apple-silicon)
3) Open your OMORI file directory (by default, the directory is `/Users/<username>/Library/Application\ Support/Steam/steamapps/common/OMORI/`
   (Alternatively, you can access this direcrtory through your Steam client by opening OMORI's page in your library, pressing on the gear icon, hover over "Manage" and press on "Open File Directory")
4) Right-click on the OMORI app and press "Show Package Contents"
5) Open `Contents`, then `Resources`, then `app.nw`.
6) Download the latest release from this repository and extract the zip file.
7) Copy the contents of the extracted `www` folder into your app.nw folder.
8) Enjoy! Mods can be installed and set up the same way as you would on any other OneLoader installation. Please follow their guides for doing so.

# Credits
This repository uses code from the following projects:
[OneLoader](https://github.com/rphsoftware/OneLoader) (MIT License)
[77Loader](https://github.com/nift4/77Loader) (MIT License)
