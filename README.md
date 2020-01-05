# TeeworldsBackup
Saving my personal data (teeworlds settings)

# Setup
**macOS**
```
cd /Users/$USER/Library/Application Support/Teeworlds
git clone https://github.com/ChillerTW/GitSettings
```
**linux**
```
cd ~/.teeworlds
git clone https://github.com/ChillerTW/GitSettings
```
**windows**
```
cd %APPDATA%\Teeworlds
git clone https://github.com/ChillerTW/GitSettings
```

Then open teeeworlds and launch console command
```
# teeworlds 0.6 / DDNet
exec GitSettings/settings_base.cfg

# teeworlds 0.7 / ZillyWoods
exec GitSettings/settings_zilly.cfg
```

Make sure to adjust the pass_settings/ directory to your needs
