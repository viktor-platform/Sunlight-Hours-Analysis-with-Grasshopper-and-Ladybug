# Sunlight-Hours-Analysis-with-Grasshopper-and-Ladybug
A VIKTOR sample app which parametrically designs a tower and runs a Ladybug sunhours analysis. 🦗🐞

**Functionality**

This version of the app connect to a Rhino Compute Server
to design a  twisting tower, configured through the app parameters. With a toggle button you can run the sun hours analysis and visualize sun path dome

Each time the user updates a parameter, the Grasshopper script runs on
Rhino Compute server that builds the geometry and performs a sunhours analysis using Ladybug.

![](C:\Users\Mostafa\Downloads\VISual.png)
**Configuration**

The Grasshopper script that is executed and the worker configuration used for this app can be found in this repo under `files`. For further documentation on how install and connect Rhino / Grasshopper to your VIKTOR app, head to our [docs](https://docs.viktor.ai/docs/create-apps/software-integrations/rhino-grasshopper/).



