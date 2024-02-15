## SOFTWARE FOR THESIS -  Beyond Certainty: Empowering Semantic Web Enabled Agents with Adaptive  Planning Strategies for Uncertain Environments

The folder contains three folder - Docs, Services and Simulation.

**Docs** - Contains all the document files such as the user survey, the responses and the informed consent form signed by the participants. A subfolder Performance contains the main performance test calls report in pdf format. This can also be visualized using the data provided in `Services\ajan_pomdp_py\tests\results` 

**Services** - Contains all the services created or needed for the thesis such as the AJAN-POMDP Service, AJAN-Airsim Service, AJAN-Editor, AJAN-service. Services/AJAN_Data contains all the behavior tree required. Deprecated contains the discarded approaches such as the DESPOT approach and RDDL-based Approach.

**Simulation** - Contains the necessary unity based simulation environment such as the Unity Robotics Warehouse and the Unity Omniverse Warehouse.

**Additional** - Contains the python version of the pomdp_py to test against the AJAN-POMDP Service

The instructions to install the individual services are present within their respective folders as README.md

The instructions assume you have the necessary performance to run the simulation and the software.
The following system configuration has worked out to be the best to run the softwares - `Intel i9 13900k, 64 GB RAM, 4060Ti 16 GB Graphics card, Min 30GB Free space in HDD`

## Running the experiments
- Once, everything is installed, run accoding to the instructions mentioned in the respective README.md
- Launch the simulation of interest if required. If realworld execution, change the parameters of AJAN-Airsim Service - `enableAirsim = False` and `enableRealWorldExecution = True` and restart the service
- Launch the AJAN Editor in the browser and load corresponding behvaior trees, actions and agents files of interest given in `Service/AJAN_Data`
- Create an instance in AJAN by moving to Instances and click `+` and run the instance. For reference, refer to the demo videos if required.