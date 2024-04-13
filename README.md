# tNYh

<!----- #### Table1: statistical significance tests ---->
<h4 align = "center">Table1: The results of statistical significance tests</h4>
<table>
    <tr>
        <th rowspan="2" >Method</th>
        <th colspan="3" >IMDB-BINARY</th>
        <th colspan="3">IMDB-MULTI</th>
        <th colspan="3">REDDIT-BINARY</th>
        <th colspan="3">REDDIT-MULTI-5K</th>
    </tr>
    <tr>
        <th>PRE</th>
        <th>RECALL</th>
        <th>F1</th>
        <th>PRE</th>
        <th>RECALL</th>
        <th>F1</td>
        <th>PRE</th>
        <th>RECALL</th>
        <th>F1</th>
        <th>PRE</th>
        <th>RECALL</th>
        <th>F1</th>
    </tr>
    <tr>
        <td nowrap="nowrap">g-U-Nets</td>
        <td nowrap="nowrap">7.21e-14</td>
        <td nowrap="nowrap">4.23e-08</td>
        <td nowrap="nowrap">1.87e-13</td>
        <td nowrap="nowrap">5.24e-17</td>
        <td nowrap="nowrap">4.81e-17</td>
        <td nowrap="nowrap">4.76e-19</td>
        <td nowrap="nowrap">5.06e-13</td>
        <td nowrap="nowrap">2.54e-19</td>
        <td nowrap="nowrap">3.17e-19</td>
        <td nowrap="nowrap">2.23e-18</td>
        <td nowrap="nowrap">3.37e-21</td>
        <td nowrap="nowrap">6.59e-18</td>
    </tr>
    <tr>
        <td nowrap="nowrap">DiffPool</td>
        <td nowrap="nowrap">2.40e-24</td>
        <td nowrap="nowrap">2.90e-23</td>
        <td nowrap="nowrap">1.21e-16</td>
        <td nowrap="nowrap">4.03e-24</td>
        <td nowrap="nowrap">9.17e-24</td>
        <td nowrap="nowrap">2.64e-14</td>
        <td nowrap="nowrap">2.66e-22</td>
        <td nowrap="nowrap">7.03e-25</td>
        <td nowrap="nowrap">5.32e-24</td>
        <td nowrap="nowrap">2.83e-20</td>
        <td nowrap="nowrap">3.62e-26</td>
        <td nowrap="nowrap">1.90e-18</td>
    </tr>
    <tr>
        <td nowrap="nowrap">SAGPool</td>
        <td nowrap="nowrap">6.72e-19</td>
        <td nowrap="nowrap">2.93e-13</td>
        <td nowrap="nowrap">4.07e-16</td>
        <td nowrap="nowrap">3.09e-21</td>
        <td nowrap="nowrap">2.64e-12</td>
        <td nowrap="nowrap">4.62e-16</td>
        <td nowrap="nowrap">3.21e-17</td>
        <td nowrap="nowrap">2.70e-19</td>
        <td nowrap="nowrap">1.01e-17</td>
        <td nowrap="nowrap">2.23e-18</td>
        <td nowrap="nowrap">7.03e-27</td>
        <td nowrap="nowrap">1.27e-18</td>
    </tr>
    <tr>
        <td nowrap="nowrap">GMT</td>
        <td nowrap="nowrap">1.15e-16</td>
        <td nowrap="nowrap">1.87e-14</td>
        <td nowrap="nowrap">9.40e-15</td>
        <td nowrap="nowrap">1.94e-15</td>
        <td nowrap="nowrap">1.83e-18</td>
        <td nowrap="nowrap">2.27e-15</td>
        <td nowrap="nowrap">5.30e-14</td>
        <td nowrap="nowrap">7.56e-18</td>
        <td nowrap="nowrap">1.29e-15</td>
        <td nowrap="nowrap">1.76e-14</td>
        <td nowrap="nowrap">1.17e-19</td>
        <td nowrap="nowrap">9.18e-20</td>
    </tr>
    <tr>
        <td nowrap="nowrap">CFGL-LCR</td>
        <td nowrap="nowrap">1.07e-13</td>
        <td nowrap="nowrap">4.19e-13</td>
        <td nowrap="nowrap">4.07e-16</td>
        <td nowrap="nowrap">5.14e-13</td>
        <td nowrap="nowrap">7.59e-17</td>
        <td nowrap="nowrap">2.77e-19</td>
        <td nowrap="nowrap">2.01e-11</td>
        <td nowrap="nowrap">1.09e-12</td>
        <td nowrap="nowrap">8.54e-17</td>
        <td nowrap="nowrap">1.31e-12</td>
        <td nowrap="nowrap">7.16e-19</td>
        <td nowrap="nowrap">3.98e-14</td>
    </tr>
    <tr>
        <td nowrap="nowrap">CFAD</td>
        <td nowrap="nowrap">9.99e-12</td>
        <td nowrap="nowrap">8.36e-12</td>
        <td nowrap="nowrap">1.93e-14</td>
        <td nowrap="nowrap">3.69e-09</td>
        <td nowrap="nowrap">9.06e-13</td>
        <td nowrap="nowrap">2.39e-18</td>
        <td nowrap="nowrap">1.82e-10</td>
        <td nowrap="nowrap">1.93e-14</td>
        <td nowrap="nowrap">5.04e-16</td>
        <td nowrap="nowrap">9.77e-12</td>
        <td nowrap="nowrap">1.23e-18</td>
        <td nowrap="nowrap">8.02e-10</td>
    </tr>
    <tr>
        <td nowrap="nowrap">CGC</td>
        <td nowrap="nowrap">2.85e-03</td>
        <td nowrap="nowrap">2.47e-02</td>
        <td nowrap="nowrap">1.01e-07</td>
        <td nowrap="nowrap">1.96e-03</td>
        <td nowrap="nowrap">2.05e-05</td>
        <td nowrap="nowrap">1.95e-03</td>
        <td nowrap="nowrap">2.17e-05</td>
        <td nowrap="nowrap">1.36e-05</td>
        <td nowrap="nowrap">2.86e-09</td>
        <td nowrap="nowrap">2.86e-09</td>
        <td nowrap="nowrap">3.05e-04</td>
        <td nowrap="nowrap">6.42e-06</td>
    </tr>
    <tr>
        <td nowrap="nowrap">CF-HGExp</td>
        <td nowrap="nowrap">1.74e-02</td>
        <td nowrap="nowrap">1.83e-02</td>
        <td nowrap="nowrap">4.48e-02</td>
        <td nowrap="nowrap">2.11e-02</td>
        <td nowrap="nowrap">1.74e-02</td>
        <td nowrap="nowrap">2.74e-02</td>
        <td nowrap="nowrap">1.67e-02</td>
        <td nowrap="nowrap">1.97e-03</td>
        <td nowrap="nowrap">1.46e-05</td>
        <td nowrap="nowrap">6.50e-08</td>
        <td nowrap="nowrap">1.97e-03</td>
        <td nowrap="nowrap">1.95e-03</td>
    </tr>
    <tr>
        <td nowrap="nowrap">OCGTL</td>
        <td nowrap="nowrap">1.25e-11</td>
        <td nowrap="nowrap">2.85e-13</td>
        <td nowrap="nowrap">1.15e-15</td>
        <td nowrap="nowrap">1.94e-15</td>
        <td nowrap="nowrap">4.65e-18</td>
        <td nowrap="nowrap">1.27e-16</td>
        <td nowrap="nowrap">1.01e-07</td>
        <td nowrap="nowrap">2.33e-13</td>
        <td nowrap="nowrap">2.91e-14</td>
        <td nowrap="nowrap">1.62e-06</td>
        <td nowrap="nowrap">1.63e-16</td>
        <td nowrap="nowrap">1.52e-09</td>
    </tr>
    <tr>
        <td nowrap="nowrap">GLocalKD</td>
        <td nowrap="nowrap">1.91e-23</td>
        <td nowrap="nowrap">8.85e-25</td>
        <td nowrap="nowrap">9.76e-25</td>
        <td nowrap="nowrap">1.68e-25</td>
        <td nowrap="nowrap">5.50e-24</td>
        <td nowrap="nowrap">4.35e-24</td>
        <td nowrap="nowrap">2.32e-23</td>
        <td nowrap="nowrap">6.27e-25</td>
        <td nowrap="nowrap">5.62e-34</td>
        <td nowrap="nowrap">2.91e-24</td>
        <td nowrap="nowrap">2.38e-24</td>
        <td nowrap="nowrap">1.23e-17</td>
    </tr>
    <tr>
        <td nowrap="nowrap">iGAD</td>
        <td nowrap="nowrap">2.64e-12</td>
        <td nowrap="nowrap">5.90e-21</td>
        <td nowrap="nowrap">5.71e-15</td>
        <td nowrap="nowrap">2.60e-11</td>
        <td nowrap="nowrap">4.38e-22</td>
        <td nowrap="nowrap">3.20e-18</td>
        <td nowrap="nowrap">8.14e-23</td>
        <td nowrap="nowrap">3.07e-22</td>
        <td nowrap="nowrap">8.74e-24</td>
        <td nowrap="nowrap">6.76e-23</td>
        <td nowrap="nowrap">1.43e-23</td>
        <td nowrap="nowrap">2.60e-18</td>
    </tr>
    <tr>
        <td nowrap="nowrap">GmapAD</td>
        <td nowrap="nowrap">7.78e-05</td>
        <td nowrap="nowrap">4.41e-02</td>
        <td nowrap="nowrap">1.73e-05</td>
        <td nowrap="nowrap">1.33e-02</td>
        <td nowrap="nowrap">3.86e-02</td>
        <td nowrap="nowrap">2.41e-02</td>
        <td nowrap="nowrap">1.73e-05</td>
        <td nowrap="nowrap">3.27e-01</td>
        <td nowrap="nowrap">6.47e-02</td>
        <td nowrap="nowrap">9.48e-05</td>
        <td nowrap="nowrap">1.68e-04</td>
        <td nowrap="nowrap">4.08e-02</td>
    </tr>
</table>
