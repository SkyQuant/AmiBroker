# Houses #

Colored house bars indicate a planet position. Digits in bracket represent a cuspid of particular house.

That kind of analysis is good on short intraday time-frames, like 1-minute.
<br>

On default <i>Placidus</i> house system is chosen, but the following house systems are implemented so far:<br>
<pre><code><br>
<br>
         ‘P’     Placidus<br>
         ‘K’     Koch<br>
         ‘O’     Porphyrius<br>
         ‘R’     Regiomontanus<br>
         ‘C’     Campanus<br>
         ‘A’ or ‘E’     Equal (cusp 1 is Ascendant)<br>
         ‘V’     Vehlow equal (Asc. in middle of house 1)<br>
         ‘W’     Whole sign <br>
         ‘X’     axial rotation system<br>
         ‘H’     azimuthal or horizontal system<br>
         ‘T’     Polich/Page (“topocentric” system)<br>
         ‘B’     Alcabitus<br>
         ‘M’     Morinus<br>
         ‘U’     Krusinski-Pisa<br>
</code></pre>
<br>
To switch it the string below must be found in <i>SkyQuant_houses</i> file and particular letter assigned to var <i>Hsys</i>.<br>
<br>
<pre><code>  Hsys = "P"; // houses system<br>
</code></pre>
<br>
<img src='https://lh3.googleusercontent.com/-UukR4s8Zx9I/T1Jf-0yxYrI/AAAAAAAAAB4/acflVfPFrlg/s1229/h1.png' />