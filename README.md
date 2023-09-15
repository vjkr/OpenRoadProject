# OpenRoadProject
Learning to use GUI through project
# Installing OpenRoad complete project 
after studying https://github.com/nickson-jose/openlane_build_script/blob/master/openlane_script.sh 
Found this error while installing git
Waiting for cache lock: Could not get lock /var/lib/dpkg/lock-frontend. It is held by process 6204
Found solution using
https://askubuntu.com/questions/15433/unable-to-lock-the-administration-directory-var-lib-dpkg-is-another-process
Cloned Openlane Build Script from NJ, this is a one stop solution for python and docker installations. We can continue independent work hereafter.
Finally installing "standalone build"
Got this... It shows sky130A files too. This might be interesting!
<img width="652" alt="image" src="https://github.com/vjkr/OpenRoadProject/assets/16399079/882bf796-694f-4df4-9750-f56620a4a7e6">
Referrring to https://github.com/efabless/openlane
to check if everything is fine

```make```
```make test```
ran successfully! Basic test passed. this is first step towards VLSI -vsd


# Comparing things with vsdflow
Found error for tcl scripts. 
/usr/bin/env: ‘tclsh’: No such file or directory
installed tcl and got rid of error
```sudo make mount```
important command to enter openlane

Projects are less. I will copy from others
<img width="614" alt="image" src="https://github.com/vjkr/OpenRoadProject/assets/16399079/363f23d1-3967-4e8d-a870-6b6ca1c48b78">
getting errors for others designs
seems I have to learn config files
<img width="905" alt="image" src="https://github.com/vjkr/OpenRoadProject/assets/16399079/c27afdb1-b428-4f14-873e-8fc873a42172">
Getting few warnings and errors with configurations. But this is fun!
<img width="960" alt="image" src="https://github.com/vjkr/OpenRoadProject/assets/16399079/983f853e-2294-4c3c-ace3-aea5b516d515">
Yet flow got completed!!!
<img width="723" alt="image" src="https://github.com/vjkr/OpenRoadProject/assets/16399079/ce781c8e-084a-4de2-b704-08853a58d45a">
# We will try ORFS!!!!!!!!!!!!!!!


