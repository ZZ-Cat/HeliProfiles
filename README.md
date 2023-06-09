# Welcome to Cassie Robinson's Heli Profiles

This is a collection of configuration profiles for remotely piloted (AKA RC) helicopters.
These configurations are used by yours truly every day, & it's my gift to the RC heli community.

At some point down the track, I would like this repo to become a hub for community-made profiles & templates that you guys can also use.

## Features at a glance

Each profile is standardised. This means that each configuration profile is as identical to each other as I can possibly make it.
I have done this for the sake of consistency across different helicopters.

### Templates

In the community directory, there are three templates that will help you get on your way:

- Ex1-DSMX-BX
  - __Flight Controller:__ BeastX Micro Beast Plus.
  - __Transmitter:__ Internal Multi-Module.
  - __Receiver:__ This can be anything with DSM2 or DSMX protocol.
- Ex2-ELRS-B2
  - __Flight Controller:__ MSH Brain2 (any & all variants).
  - __Transmitter:__ External ExpressLRS transmitter module (EG RadioMaster Ranger).
  - __Receiver:__ ExpressLRS receiver (EG RadioMaster RP3).
- EX3-OMP-OMP
  - __Flight Controller:__ OMPHOBBY flight controller for M1 or M2 helicopters.
  - __Transmitter:__ Internal Multi-Module.
  - __Receiver:__ Built-in receiver in the OMPHOBBY flight controller.

These templates are (what I consider to be) "traditional" helicopter setups, but with an EdgeTX twist.
They are also _very simplified_ versions of the profiles that I use for Tesla, Nemo, & Sieglinde, respectively.

Each template has the following features:

- Bank Switching.
- Control Isolation.
- Pit Mode.
- RPM Switching.
- Two-Step Safety Arming.

### Directories

You will notice that under both the Community & Main subfolders, the folder directories are identical to what you see on your controller's micro SD card. This is because each one is literally drop-&-drag compatible, & it greatly streamlines the installation process.

## Compatibility

So far, these profiles & templates are only compatible with the RadioMaster TX16S, but that is because I _only_ have a RadioMaster TX16S on hand & it's easy for me to test these profiles & templates on my RadioMaster.

I do plan on adding more compatible controllers to these profiles & templates. With that being said, I will need your help in testing everything & making sure it's working as intended. If you happen to spot a bug in my profiles (not with EdgeTX itself), consider opening an Issue.

Generally speaking, if your controller runs EdgeTX, it is very likely that compatibility can be added to these profiles.

## Contributing & Self-builds

### For folks that want to "Roll your own"

#### Downloading from my GitHub Repository

To obtain, do the following:

1. Click the green `<> Code` button.
2. Select `Download ZIP`
3. Save the downloaded file to a convenient location.

#### 7-Zip users

1. Open the ZIP file in 7-Zip.
2. Navigate to `..\HeliProfiles-Main-Trunk.zip\HeliProfiles-Main-Trunk\Profiles\Main\Companion\Profiles`
3. Highlight `HeliProfiles.etx`.
4. Click `Extract`.
5. In the dialog box, set the file destination to the same directory that you store the rest of your EdgeTX Companion profiles. For me, I keep mine in `C:\%userprofile%\OneDrive\EdgeTX\Companion\Profiles`
6. Click `OK`.

#### Windows ZIP file manager

1. Right click the ZIP file & select `Extract All...`
2. The default destination directory will be the same as where the ZIP file is stored.
3. Ensure `Show extracted contents when complete` is selected.
4. Hit `OK`.
5. Navigate to `..\HeliProfiles-Main-Trunk\Profiles\Main\Companion\Profiles`.
6. Copy the `HeliProfiles.etx` file to the same directory where you store the rest of your EdgeTX Companion profiles. For me, I keep mine in `C:\%userprofile%\OneDrive\EdgeTX\Companion\Profiles`

#### In EdgeTX Companion

1. Do `ctrl+o` & navigate to your directory where you store your EdgeTX Companion profiles. For me, I keep mine in `C:\%userprofile%\OneDrive\EdgeTX\Companion\Profiles`
2. Double-click `HeliProfiles.etx`
3. By rights, EdgeTX Companion should load the source files for my Heli Profiles with impunity.

### Contributing

__COMING SOON!__
