# TimeZones #

Each TimeZones file include information about particular place (usually city) and consist of the next points
  * Latitude
  * Longitude
  * Default Time zone
  * Time Shift coefficients
  * List of time changes


For example, for New York it look like that
```
[atlas],40.776382,-73.966484,NewYork
[UTC],-5,-1,0,
```

<br>
Current version includes the TimeZones files for the following cities:<br>
<ul><li>Moscow (default)<br>
</li><li>London<br>
</li><li>New York<br>
</li><li>Chicago<br>
</li><li>Frankfurt<br>
</li><li>Sydney<br>
</li><li>Hong Kong<br>
</li><li>Mumbai</li></ul>

To change default place the string in <i>SQ_header.afl</i> must be corrected.<br>
<pre><code>  tzchoice = ParamList("Select TimeZone", "Moscow|London|NewYork|Chicago|Frankfurt|Sydney|HongKong|Mumbai" );<br>
</code></pre>

<br>
<img src='https://lh3.googleusercontent.com/-eznfHWvw6tM/T1Jf_igtLxI/AAAAAAAAABs/fsANzMdl9Ok/s1229/h3msk.png' />