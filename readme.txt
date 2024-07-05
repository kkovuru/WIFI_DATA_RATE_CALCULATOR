                                        AUTHOR : KISHORE KUMAR KOVURU
                                        -----------------------------

                     Wi-FI DATA RATE CALCULATOR APPLICATION TOOL USING PYTHON IN WINDOWS OPERATING SYSTEM
                     ------------------------------------------------------------------------------------

This Python GUI Tool Calculates 802.11ax, 802.11ac, 802.11n and Legacy Data Rates for various parameters of OFDMA and OFDM in Wi-FI like Bandwidth(BW), 
Spatial Streams(SS), Modulation & Coding Scheme(MCS),Resource Unit Allocation(RU), Guard Interval(GI) Etc.


Rules:
-----

a) Any Parameters in "Option Type" as Default cannot be modified and it calculates data rate of all possible combinations in given wi-fi technology
b) Only parameters "[a,b,c,d,e,f,g,h,i]" inside "Data Rate Calculation" Field should be changed if "Option Type" is "Custom". Also elements a,b,c,d,e,f,g,h,i etc 
   should be valid for given wi-fi technology
c) MCS:[a,b,c,d,e,f,g,h,i]:RU:[j,k,l,m]:SS:[n,o,p,q]:GI:[r,s,t,u] (or) MCS:[a,b,c,d,e,f,g,h,i]:BW:[j,k,l,m]:SS:[n,o,p,q]:GI:[r,s,t,u] valid for 
   "Custom-802.11ax_OFDMA-HE"
d) MCS:[a,b,c,d,e,f,g,h,i]:BW:[j,k,l,m]:SS:[n,o,p,q]:GI:[r,s,t,u] valid for "Custom-802.11ac_OFDM-VHT", "Custom-802.11n_OFDM-HT" and "Custom-802.11ag_OFDM-Legacy" 
e) The Data rate calculation is executed once you select any of the field like "Default-802.11ac_OFDM-VHT-ALL" and use the load button to load it.
f) To update the custom parameters in Data rate calculation select particular field and change to required parameters using update button update and then 
   using refresh button to refresh it and then calculate data rate date for changed parameters using load button.
g) ADD and DELETE for New fields only.



For Windows users:
-----------------

Run WiFi_Data Rate_Calculator_GUI.exe" in Windows Operating System

