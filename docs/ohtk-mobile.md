# OHTK Mobile

### What you'll need

- flutter
- android studio

#### Install

Get latest version of ohtk-mobile from github:

```git clone https://github.com/onehealthtoolkit/ohtk-mobile.git```


#### Change server to test server
Change settings to 
```opensur.test```

#### Run flutter build command
```	flutter pub run build_runner build --delete-conflicting-outputs```

If necessary, add the Android emulator to your path
```export PATH=$PATH:~/Library/Android/sdk/emulator/```

#### Add Google Maps API Key
Add your Google Maps API to your local.properties file

#### Start Emulator
run

```emulator -writable-system -netdelay none -netspeed full -avd Nexus_6```

Then run your program
Ex: For VS Studio go Run > Run without Debugging

Now you just need to login and submit some reports. 