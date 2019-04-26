# <img width="50px" height="50px" src="logo_small.png" alt="Logo"/> AHU-Walkaround ![Build status](https://build.appcenter.ms/v0.1/apps/e685da99-3861-40df-ac88-20c52000ae39/branches/master/badge)
Android application for performing regular quick checks on AHU ventilation plants/units and producing a pdf report for managers to act on and action remedial works.  
This is a work in progress.

## Installation
Installation of the app is via automatic updates or the app can be directly downloaded from the Microsoft Visual Stuio App Center.
[App Center Download Page](https://install.appcenter.ms/users/smurf0969/apps/ahuwalkaround_android/distribution_groups/public)

> ### Configuration  
> AHU's can be added and removed in edit mode.  
> To switch between modes you must turn on or off edit mode in the settings then restart the app. 
>  
> Currently to add/remove new buildings needs to be done manually by editing buildings.json file.  
> #### buildings.json
> ```
> [
>   {
>     "Abbrev": "DEMO",
>     "Name": "Demo Building"
>   },
>   {
>     "Abbrev": "YOUR_NEW_BUILDING",
>     "Name": "My Building"
>   }
> ]
> ```
> If adding a new building, a new AHU list file will also need to be added manually with a blank array.  
> The AHU list file name needs to match the building abbreviation set in buildings.json and have the json extension.  
> #### YOUR_NEW_BUILDING.json
> ```
> []
> ```

## Bugs/Issues
Whilst the app should automatically notify of any errors or crashes, this is unfortunatly not always the case.
If you are experiencing any problems please take a look at the [Issues](/issues) page to see if others are experiencing the same prolem, and if not raise an issue yourself.
I will endevour to rectify any problems as wuickly as possible.

## Feature Requests
If you have an additional functions/features you feel that should be included in future releases of the software, either request it via raising an [issue](/issues) or contact me personally via email [smurf0969-github@bfam.co.uk](mailto:smurf0969-github@bfam.co.uk)