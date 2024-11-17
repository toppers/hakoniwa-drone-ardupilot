# hakoniwa-drone-ardupilot


## memo


```bash
pip3 install --user pymavlink MAVProxy
cd ardupilot/
./Tools/environment_install/install-prereqs-ubuntu.sh -y
. ~/.profile 
cd ArduCopter/
python3 ../Tools/autotest/sim_vehicle.py -w 
python3 ../Tools/autotest/sim_vehicle.py --console --map -w
```

