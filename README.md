# FLAI
Alpaca Airways liveries for FSX's and P3D's [FLAI](http://flai.bvartcc.com/) 
add-on used when flying online together on VATSIM.

## Aircraft included

- Airbus A319 (IAE) by Steven Beeckman (Reworked a @jamlen CSL)
- Boeing 737-800 (both Alpaca Airways and Ameripaca Airways)
- Boeing 767-300 winglets by Steven Beeckman

## Installation instructions
You need to locate your FLAi path. You can find it by opening the FLAi 
Operations Center.

Inside that path you'll see a `SimObjects` folder. This folder contains another 
`Airplanes` folder, which in turn, contains all the airplane models used by 
FLAi.

- Add the `texture.VCP-Alpaca` folder to each respective aircraft.
- Make sure to register the new texture into each aircraft's `aircraft.cfg`.
- Register your models into vPilot by adding the `FLAI-Alpaca-VCP.vmr` file. 
(If you want you can switch between the Alpaca Airways and the Ameripaca Airways 
models, just choose for `ModelName` the right `title` from the `aircraft.cfg` 
file.)