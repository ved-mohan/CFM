# CFM
Locating best new locations for Community Farmers Market within MARTA bus stops

# Detailed info
This was a simple project done for CFM. Attached and aggregated census tract data to each MARTA bus stop. This allowed identification of the candidate bus routes for expansion given metrics of food insecurity. 

Bus stop data was sourced from MARTA developer's GTSF (General transit feed specification) in Nov 2020. After stops were compiled into routes, Latitude and longtiude data was run through an FDA api to find each stop's respective census tract. Finally, aggregated analysis was conducted to identify best candidates for expansion. 

# Future work
This project will lend itself handily to an optimization framework. The system has dual objectives: Minimize distance from our warehouse (singular) and volunteer travel time while maximizing food insecure household reach.
