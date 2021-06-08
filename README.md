<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Dap-Bot Command</h3>

  <p align="center">
    Data analytics and process
    <br />
    <a href="https://github.com/d3dmenu/DAP/blob/main/README.md"><strong>Explore the docs »</strong></a>
    <br />
<!--     <br />
    <a href="https://github.com/d3dmenu/DAP/blob/main/README.md">View Demo</a>
    ·
    <a href="https://github.com/d3dmenu/DAP/blob/main/README.md">Report Bug</a>
    ·
    <a href="https://github.com/d3dmenu/DAP/blob/main/README.md">Request Feature</a>
    -->
  </p>
</p> 

<!-- ABOUT THE PROJECT -->
## DAP Cashflow dashboard features <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px">

Features:
* Select a range of timeline.
* Generate a new file of the dashboard `you can edit the report that you've retrieved`
* You can also optionally adjust the formulas inside the dashboard.

Here are the sample commands to retrieve the dashboard:

### Command

1. To retrieve the **whole timeline**
   ```sh
   @DAP make all
   ```
2. To retrieve only **one specific month**
   ```sh
   @DAP make June 2021
   ```
3. To retrieve **a specific range of timeline**, e.g. between January to December 2021
   ```sh
   @DAP make January December 2021

   @DAP make January 2021 December 2022

   @DAP make January December 2021 2022
   ```
```diff
+ You can use the abbreviated month name!
```
