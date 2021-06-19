# Car-photo-generation-from-Carla
Dataset generation for camera pose estimation with Carla simulator and python. 
This script should be placed under examples of PythonAPI of carla simulator folder.
Carla version used is 0.9.11 and python 3.7 <br>
This code takes photos of a car in different angles and positions. <br>
You have 18 car models by default in carla but you can add other car models.<br>
It is based on client_bounding_boxes.py <br>
To change the car model you have to change the number n which  is in [0..18] <br>
car_bp = self.world.get_blueprint_library().filter('vehicle*')[n] <br>
To change the location of the car you have to change n in this line by a number <br>
spawn_point=self.world.get_map().get_spawn_points()[n]

Carla installation (download carla (install dependencies with python -m pip install -r requirements.txt) , python (make sure it's x64) and  pip under windows with curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py and then python get-pip.py, 
to install requiered libs with  pip install -r requirements.txt and then install mathutils with pip install mathutils)
launch program from cmd  with python dataset_generation.py
this commands are valid for linux 

