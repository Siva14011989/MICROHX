Microchannel Heat Exchanger Simulator Deployment Guide
=================================================

Description:
------------
This simulator calculates thermal performance for microchannel heat exchangers (Radiator, Evaporator, Condenser) with support for:
- Multiple fin types: Plain, OSF, Louvered, Wavy
- Phase change materials (PCM)
- Multi-zone geometry and multi-fluid simulations
- Batch simulations from Excel
- NTU vs. UA plotting and fin optimization
- Export results and charts to PDF (optional enhancement)

How to Run This App Locally:
----------------------------
1. Ensure Python 3.8 or later is installed.
2. Install required packages:
   pip install -r requirements.txt

3. Launch the Streamlit app:
   streamlit run microchannel_simulator.py

Files Included:
---------------
- microchannel_simulator.py : Main simulation app
- requirements.txt : Required Python libraries
- README.txt : Deployment instructions

Deployment on Streamlit Cloud:
------------------------------
1. Visit https://streamlit.io/cloud and sign in.
2. Upload this folder (or GitHub repo) containing the files.
3. Streamlit Cloud will auto-run microchannel_simulator.py.
