# Object-Detection
Detecting vehicles and warn them if they get close to another vehicle.

### Getting started

- Install required packages

  ```sh
  pip install tensorflow-gpu
  pip install pycocotools
  pip install winsound
  pip install opencv-python
  pip install numpy
  pip install matplotlib
  ```

- GPU configurations
  - Download CudaNN for NVIDIA
  - Update the graphic drivers
  - Make sure to install all the required attributes.

- Models from TensorFlow

  ```sh
  git clone https://github.com/tensorflow/models
  cd models/research
  protoc object_detection/protos/*.proto --python_out=.
  pip install object_detection
  ```

- Run
  
  ```sh
  python vehicle_detector.py
  ```

### Result
  <img src="https://github.com/Jaay7/Object-Detection/assets/73716175/90073821-74e0-4b4d-be30-2df4cbe96ec5" alt="output1" height="280" />
  <img src="https://github.com/Jaay7/Object-Detection/assets/73716175/dcb89894-eed3-471f-b7c3-1b294116dee7" alt="output2" height="280" />

