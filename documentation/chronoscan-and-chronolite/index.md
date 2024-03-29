
# ChronoScan & ChronoLite

ChronoScan Capture Suite and ChronoLite are two different applications.

* ChronoScan Capture is indepentent of ChronoLite and it can be used as usual as your document managing application.
* ChronoLite in the other hand, is a ChronoScan Plug-in and in order to be used, it needs a ChronoScan Capture application installed.

When ChronoScan Capture Suite is installed in your pc, it will automatically install ChronoLite as a separate and optional destktop application.

<!--![Chronoscan Capture Suite launcher icon](./../../images/chronoscan_logo.png)-->
<br />
<div style='display: flex;
            text-align: center;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 0 10%;'>
    <div style=' display: inline-block;'>
        <!--<img align="center" width="40" src="./../../images/chronoscan_logo.png" alt="Chronoscan Capture Suite launcher icon">-->

![Chronoscan Capture Suite launcher icon](./../../images/chronoscan_logo_40.png)  
        <small class="img_caption">ChronoScan launcher icon</small>
    </div>
    <div style=' display: inline-block;'>
        <!--<img align="center" src="./../../images/clock_forward_40.png" alt="ChronoLite launcher icon">-->

![ChronoLite launcher icon](./../../images/app_ico_40.png)    
        <small class="img_caption">ChronoLite launcher icon</small>
    </div>
</div>
<br />

## Starting ChronoLite

* If you have more than one ChronoScan configuration You can start ChronoLite from ChronoScan by opening ChronoScan and clicking in the <i>Run ChronoLite button</i>

> **Note:** When running ChronoLite this way, ChronoLite will automatically be opened with the selected configuration

![Run ChronoLite](./../../images/documentation/chronoscan-and-chronolite/chronoscan_chronolite_launcher.png)  
<small class="img_caption">Running ChronoLite from ChronoScan Capture Suite.</small>

## Command line

Chronolite can be run directly from the command line adding the argument **-lite** to ChronoScan.exe:

>_since: 0.2.60\afcaa34 (June2021)_

```
cmd>${ChronoScan_Installation_Directory}\ChronoScan\Bin\ChronoScan.exe -customdir:"${ChronoScan_Configuration_Directory}\Chronoscan.[Config_Name]" -lite
```

