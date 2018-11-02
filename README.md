# darkKik
Converting stock kik ui to a dark themed variant

What this guide/repository covers
1. Modifying Colors.xml (partially to convert to dark theme, partially to change other colors)
2. Modifying res/layout and res/layout-v17 (finishing touches on the dark theme)
3. Adding the A/B testing menu (optional, enables a hidden menu within kik with many customization options)
4. Changing the package name (optional as well, packagechanger tool from the hyper6 repository will be used)

# The Easy Way
1. Get a copy of stock kik (must match version code to folder name in repository) (we are starting with kik 18.4 and moving
upwards as kik releases updates)
2. Decompile with apktool (apktool d kik.apk)
3. Delete res/layout and replace with the layout folder from this repository
4. Delete res/layout-v17 and replace with the layout-v17 folder from this repository
5. Delete res/values/colors.xml and replace with the colors.xml file from this repository
6. Add android:debuggable="true" to AndroidManifest.xml under the <application tag)
 6a. If you have problems with this,download the AndroidManifest from this repository, delete the old manifest file
 and add the one you just downloaded
7. Download the packagechanger scripts from my hyper6 repository (please read then intructions, the tool is still a beta)
8. Change the package name using my tool
9. Recompile with apktool (apktool b kik -o yourmodnamegoeshere.apk)
10. Sign the apk (apk-signer is a great tool and works on Windows AND Android ANDDD Linux ;)
11. Install the apk and enjoy your new retheme

# The Hard Way
Coming Soon...
