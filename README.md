# Sunlight-Hours-Analysis-with-Grasshopper-and-Ladybug
A VIKTOR sample app which parametrically designs a tower and runs a Ladybug sunhours analysis. 🦗🐞

**Functionality**

This version of the app connect to a Rhino Compute Server
to design a  twisting tower, configured through the app parameters. With a toggle button you can run the sun hours analysis and visualize sun path dome

Each time the user updates a parameter, the Grasshopper script runs on
Rhino Compute server that builds the geometry and performs a sunhours analysis using Ladybug.
<img width="1276" alt="VISual" src="https://github.com/viktor-platform/Sunlight-Hours-Analysis-with-Grasshopper-and-Ladybug/assets/144118685/3517f8a4-2edc-412e-9cf0-9997d4912c51">


**Configuration**

The Grasshopper script can be found in this repo under `files`. For further documentation on how install and connect Rhino / Grasshopper to your VIKTOR app, head to our [docs](https://docs.viktor.ai/docs/create-apps/software-integrations/rhino-grasshopper/).



