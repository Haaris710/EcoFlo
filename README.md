# HackHarvard

## Project Overview
This source code supplements various hardware components of a prototype, home-installed system which allows users to pay for their electricity usage using a stream of microtransactions, made possible mainly by the Interledger API.

## Motivation for the Project
The main real-world issue that this challenge sought to solve, was that of disruptive power-cuts and load-shedding events in developing countries. In a typical city or region troubled with disruptive power-cuts, the amount of energy generated (in kWh) cannot meet consumer energy demands. When the gap between supply and demand starts to grow, power-cuts and load-shedding events are instituted to control energy usage, a process which is quite disruptive to residents and organizations.

One of the contributing factors to this situation is the fact that the consumers are essentially unaware of the consequences of energy wastage and the correlation between energy wastage and future power-cuts/load-shedding events.

The system we designed switched consumers from a monthly charge to a real-time charge. Consumers would be paying in real-time for their energy usage via microtransactions.

The benefit of this is that power-generation/distribution entities can change the cost of each micro-packet of energy (measured in micro-Watt-seconds) in real-time, depending on the available energy in a given grid region. This has the effect of naturally incentivizing people to use less energy during a shortage, and also to use less energy overall.

It was our hope and belief that such a system could be used to provide a better solution to the currently implemented method, allowing people to live better lives, and to conserve energy as a whole in an attempt to make a positive impact on the environment.

## System Overview
### Arduino Uno as a Sensor
