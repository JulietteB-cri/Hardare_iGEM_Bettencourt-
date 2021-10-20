# Hardare_iGEM_Bettencourt


Here is the repository for all the documentation on the Hardware design of Paris Bettencourt team 

Members of this project: 
- Daria Fedorova
- Sarah Haggenmüller
- Etienne Lemiere
- Nathália Raquel de Souza Fernandes
- Michael Sedbon

We wished to create our bioreactor to automatize our biological process and increase the biosafety.

There is different elements in our bioreactor :
- One tank to countain E. coli strains
- A Second tank to countain minicell to produce pigments.
- An Airpump to mix the liquid of the first tank, and to send to the second tank the E. coli bath.
- A Liquid handling pump to extract the liquid from the second tank (countaining minicells and pigments) to another tank.
- One heating system (with a thermostat controlled with arduino) for the first tank, put at 30 degrees.
- Another heating system (with a thermostat controlled with arduino) for the second tank, put at 42 degrees.
- Two thermometers (in each tank) to send informations from the tanks to the arduino (for thermostat system).
- A turbidity sensor to control density of E. coli inside the first tank.
- Different relays to transform 5V to 12V
- power supply

Concerning the Arduino system (That you can find in the GitHub): 
- There is 2 thermostats system to manage temperatures inside tanks
- Arduino receive data from the turbidity sensor, it allows to know the density of E. coli.
- When the density is sufficient (depending what we expected), the pump send the liquid in the second tank.
- There is new conditions in the second tank to allow minicell to produce pigments

