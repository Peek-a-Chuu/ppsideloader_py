# ++sideloader_py
an python implementatio of @eni9889's ppsideloader

# How to use
1. Get an ipa from your app
2. Extract the .ipa and compress the content of "Payload/AppName.app/" (the inside of "AppName.app") to "app.zip"
3. Get your Tweak and compress to "Tweak.zip"
4. Copy both zips into the main directory
5. Open the "ppsiderloader_py.py" with python
6. Click on "Extract Files", it will setup everything
7. Enter the App Exec name in the box and click on "Hex edit app"<br>

**AS OF RIGHT NOW THIS FEATURE DOES NOT WORK!!! YOU GET MANUAL INSTRUCTIONS ON HOW TO HEX THE APP EXEC IN THE CONSOLE. LOOKING INTO IMPLEMTING THIS**<br>

8. Click on "Creat IPA" and your ipa with the ++ tweak will be made.

# Credits
- <a href="https://github.com/eni9889">@eni9889</a> for <a href="https://github.com/eni9889/ppsideloader">The Original ppsideloader</a>
- <a href="https://github.com/julioverne/">@julioverne</a> for <a href="https://github.com/julioverne/libloader-sideloader">libloader</a>
- <a href="https://github.com/saurik/">@saurik</a> for CydiaSubstrate.framework