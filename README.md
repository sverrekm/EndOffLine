Node-RED Project Documentation
This repository contains a Node-RED project designed for various testing and measurement tasks. The flow is organized into multiple tabs that handle different stages of the process. Below is a brief overview of each tab and its purpose.

Project Overview
Tabs in the Project
Kjør test - This tab is used for initiating the testing process.

Setup - Configurations and setup parameters for the test environment.

Måling 1 (Motstand) - Resistance measurement.

Måling 2 (Fas/GND) - Phase to ground measurement.

Måling 3 (Motstand GND/Skall) - Ground to Shell resistance measurement.

Måling 4 (ACW) - ACW (Alternating Current Wattage) measurement.

Måling 5 IR - Infrared testing and measurement.

Måling 6 GB - Ground Bound testing.

Multimeter 4W - Multimeter measurements.

IR - Infrared related measurements.

Ground Bound - Ground bound measurements.

ACW - Additional ACW measurements.

Utregning - Calculations for processing results.

Visning - Display of processed results.

Oppslag - Lookup information for test parameters.

Kjøring av test dummyer - Running tests with dummy data for verification.

Test Raport - Generation of test reports.

PFC200 - Interface for communication with PFC200 hardware.

Standard Komandoer - Standard commands for controlling the system.

Laser Merking - Laser marking integration.

Setup Instructions
Prerequisites
Docker container running Node-RED with required dependencies.

Serial ports (such as /dev/ttyO1) configured for connection.

Running the Project
Clone the repository and import the flow file into your Node-RED instance.

Set up required configurations for database, serial ports, or specific test parameters within the respective tabs.

Deploy the flows, and the testing process should be ready for execution.

Dependencies
The following Node-RED nodes are required for the project:

node-red-dashboard

node-red-contrib-ui-led

node-red-contrib-postgresql

node-red-node-serialport

@wago/node-red-io-api

Install these dependencies by running the following command in your Node-RED container:

bash
Copy
npm install node-red-dashboard node-red-contrib-postgresql node-red-node-serialport @wago/node-red-io-api
License
This project is licensed under the MIT License - see the LICENSE file for details.

This template includes sections for project setup, dependencies, and descriptions for each tab within your Node-RED flow. You can further customize and expand this based on your specific project details and usage instructions.