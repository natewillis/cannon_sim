# cannon_sim
Shooting cannonballs!

## Installation
I grabbed the latest jsbsim wheel from the [jsbsim github](https://github.com/JSBSim-Team/jsbsim).  Grab the latest
version or just use jsbsim wheel included in the whl directory and install via pip first: 

```pip install JSBSim-1.1.0.dev1-688-cp37-cp37m-win_amd64.whl```

Then install the rest of the requirements:

``` pip install  -r requirements.txt ```

## Before running the code

In order to see the cesium visualizations, you'll need a webserver running locally.  In your local terminal, make sure 
you're in the cannon_sim directory and  run the following command (on python 3):

``` python -m http.server ```

Make sure to leave that terminal alone as it will be running the webserver you need for the visualzations to popup in.

## Running the code

In the main subroutine of BallMaker.py there is a user_parameters dictionary with launch and target lat/lons that you 
can change.  The altitudes currently aren't used.  The just run the main sub (in pycharm just hit the green triangle)
