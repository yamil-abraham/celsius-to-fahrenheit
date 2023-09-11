# celsius-to-fahrenheit
- This is a real-time Celsius to Fahrenheit converter using Tensorflow.js, based on a model trained in Python with TensorFlow.

  1. Download the repository.
  2. Download the repository wherever you want on your computer.

 # Starts a server in the folder

- This project uses a Tensorflow.js model, which to load requires access via http/https. For that you can use any server, but here is a way to do it:

  1. Download Python to your computer
  2. Open a command line or terminal
  3. Navigate to the folder where you downloaded the repository
  4. Run the command python -m http.server 8000
  5. Open a browser and go to http://localhost:8000


- **Note:** the following files must be in the same directory otherwise the APP does not work correctly. List:
  1. model.json
  2. index.html
  3. group1-shard1of1.bin
  4. celsius_to_fahrenheit.h5

# APP

- Move the Celsius slider, and the forecast will be displayed in Fahrenheit.

![alt text](https://github.com/eyamilabraham/celsius-to-fahrenheit/blob/main/pic1.jpg)
