# BackPropagation
Implemention of a full backprop algorithm using only numpy. 
I assume sigmoid activation across all layers and a single value in the output layer.

I trained it on the Bike Sharing dataset.

Use the following features from the data:

temp
atemp
hum
windspeed
weekday

The response variable is, raw["success"] = raw["cnt"] > (raw["cnt"].describe()["mean"]).

The architecture of the network : [5, 40, 30, 10, 7, 5, 3, 1].

Use batch_size=8, and train it for 100 epochs on the train set.

Then, ploted loss per epoch.
