# dji-obj_detection

## First step : 

Firstly, making a mobile app (android) to get the video feed from the dji fly mini 4 drone and visualize it. -> dji SDK  
Analyze this feed with the yoloV8 model to detect objects. 

## Second step (maybe the last one) : 

Finally, according to the object (human, car, bike) detected and the confidence, move towards the object. 
We must calculate the distance to the object, and manage the movement to go towards the object. 

Distance en metres (D) = (taille reelle de l'object en metres * focale de la camera en pixel) / taille de l'objet dans l'image en pixels

Don't know yet how to proceed with this part. 
