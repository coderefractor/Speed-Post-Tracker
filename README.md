# Speed Post Tracking

A nifty library to provide easy access to track Speed Post or EMS India Post packages.

It is a general brand name for accelerated delivery services provided by inpependant companies. There are 3 different types of Speed Post carriers:

1. India Post EMS: India Post has been affiliated with international EMS network to provide a common tracking portal for all your parcels.
2. International: International Speed Post provides courier services outside of India. 
3. Singapore Post: This is a completely unrelated carrier which is based in Singapore.

## How Does it Work?

This library uses a simple and straight-forward procedure to provide tracking features. In the first initialization step, it connects with the API service (This is in configurable based on your end point. Next, the track package call takes two parameters namely tracking number and carrier as input.

Once you provide these details and make the call, it queries the API server and fetches the JSON response. The JSON response is then parsed and converted into a plaintext array. This data is returned to the caller.


This is possible through the [My Government](https://mygov.in/) initiative of the Indian I.T ministry. It provides datasets and APIs for gathering public data for free.
