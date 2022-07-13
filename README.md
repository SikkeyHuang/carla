# Notes for Carla installation

Install from package (Don't build from source)

Change python version to 3.7

For every new terminal: 

conda activate py37

sudo chmod -R 777 /opt/carla-simulator/

Install carla-simulation
Install carla client


Open the simulator (server)

cd /opt/carla-simulator && ./CarlaUE4.sh 

change the config of the environment

cd /opt/carla-simulator/PythonAPI/util/

./config.py --map Town01
./config.py --no-rendering


add an object

cd /opt/carla-simulator/PythonAPI/examples/examples/

python record_datas_1.py

get the location of all the spawn locations

python extract_spawn_points.py 
