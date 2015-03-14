# Installation #

[AmiBroker](http://amibroker.com/) **32-bit** version not older then **5.40** must be installed first.

SkyQuant plug-in installation must be done to the main AmiBroker folder. **BackUp** SkyQuant previous files before this stage.

If formulas folder is different then native AmiBroker folder change the path in _SkyQuant.ini_ settings file:
```
  [PATH]
  TZpath=,C:\Program Files (x86)\AmiBrokerBeta\,
  ABpath=,C:\Program Files (x86)\AmiBrokerBeta\,
```


where
  * _TZpath_ is a part of path to TimeZones files folder
  * _ABpath_ is a part of path to SkyQuant formulas

<br><br>
<h1>Open Source</h1>

Whole solution consist of<br>
<ul><li>SkyQuant AFL codes<br>
</li><li>TmeZone files<br>
</li><li>Swiss Ephemeris<br>
</li><li>SkyQuant.dll</li></ul>

SkyQuant.dll plays role of a link between Swiss Ephemeris and the end-user application scripts. It's necessary to build new project to improve a functionality by adding correction to SkyQuant.dll. Sources with detailed description for that are placed at:<br>
<ol><li><a href='http://amibroker.com/download.html'>AmiBroker Developlent Kit (ADK)</a>
</li><li><a href='http://www.astro.com/swisseph/'>Swiss Ephemeris</a>
</li><li><i>Functions.cpp</i> in <a href='http://code.google.com/p/skyquant/downloads/list'>Downloads area</a>
</li><li>AFL scripts are packed in installer <i>SkyQuantSetup.exe</i>