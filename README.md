# AstroShield-V3.0

AstroShield - Interactive Satellite Tracker

AstroShield is a client-side web application for interactive satellite tracking and near-miss prediction. It uses satellite.js to perform SGP4 orbital propagation directly in the browser, providing a real-time visualization and analysis of potential satellite conjunctions.

Features

    Interactive Visualization: A dynamic HTML5 Canvas displays a stylized view of the Earth and orbiting satellites.

    TLE Data Input: Easily paste custom TLE (Two-Line Element set) data for any satellite.

    Near-Miss Prediction: Analyzes orbital paths to identify and list potential near-misses based on a user-defined proximity threshold.

    Configurable Parameters: Adjust the prediction window (in minutes) and proximity threshold (in kilometers) to customize the analysis.

    Demo Mode: Instantly load TLE data for the ISS (Zarya) and the Hubble Space Telescope (HST) to see the application in action.

    Modern UI: A clean, responsive, and space-themed interface built with pure HTML and CSS.

  How to Use:

  
  Input Data:

    Click  Load Demo to use pre-loaded TLEs for the ISS and HST.

    Or, paste your own TLE data (in 3-line format: name, line 1, line 2) into the TLE Data Input text area.

Set Parameters:

    Adjust the Prediction Window to set how far into the future the analysis should run.

    Set the Proximity Threshold to define the minimum distance for a near-miss alert.

Run Prediction: Click the  Run Prediction button.

View Results:
