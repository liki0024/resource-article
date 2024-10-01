# Introduction:
The MQ135 is a gas sensor designed to detect various gases, particularly air quality in industrial settings and homes. It is highly sensitive to gases such as ammonia (NH3), sulfur (S), benzene (C6H6), smoke, and carbon dioxide (CO2). The sensor operates by providing an analog output that is proportional to the concentration of gases in the environment. Its low cost, wide sensitivity range, and simple interface make it a popular choice in air quality monitoring systems.

## Key Features:
* Gas Detected: Ammonia (NH3), Nitrogen Oxides (NOx), Alcohol, Benzene, Smoke, Carbon Dioxide (CO2)
* Operating Voltage: 5V
* Current Consumption: 40 mA
* Preheating Time: 24-48 hours for calibration and stable operation
* Analog Output: The sensor provides an analog voltage proportional to the gas concentration.
* Sensitivity Range: 10 ppm to 1000 ppm

## Working Principle:
The MQ135 gas sensor works on the principle of chemiresistance, where the resistance of the sensing material changes when it is exposed to certain gases. The sensor consists of a tin dioxide (SnO2) sensing layer, which has low conductivity in clean air. When target gases are present, they react with the SnO2 surface, reducing the resistance and allowing more current to flow through the sensor. This change in resistance is measured and converted into an analog voltage output.

## Calibration for Different Gases:
The MQ135 sensor can detect multiple gases, and each gas has a unique calibration curve. These curves are typically logarithmic and are plotted on a graph of the sensor’s resistance ratio (RS/R0) against the concentration of the gas in parts per million (ppm). Below are some of the common calibration details for various gases:

1. Carbon Dioxide (CO2):

The sensor responds to CO2 concentrations between 200 and 5000 ppm.
The calibration graph is typically nonlinear and needs to be adjusted for sensitivity at low concentrations.
2. Ammonia (NH3):

The MQ135 can detect ammonia at concentrations between 10 and 1000 ppm.
Higher concentrations of ammonia reduce the sensor resistance, causing a higher analog output voltage.
3. Benzene (C6H6):

Detects benzene concentrations ranging from 10 to 1000 ppm.
Benzene has a high impact on the sensor's resistance, making the sensor highly sensitive to this gas.
## Freundlich Adsorption Isotherm
The MQ135 sensor follows a variant of the Freundlich Adsorption Theorem, which explains the relationship between the gas concentration and the adsorption onto the sensor surface. The general form of the Freundlich equation is:

𝑆=𝐾⋅𝐶1/𝑛S=K⋅C 1/n
 

Where:


S = amount of gas adsorbed onto the surface (measured through change in sensor resistance),
C = concentration of the gas in ppm,
K and 1/𝑛
1/n are constants dependent on the specific gas.
This relationship helps in determining gas concentrations at lower levels, where the change in resistance is proportional to the gas concentration. This behavior is typically plotted as a logarithmic curve. For the MQ135, the curve shows a decreasing RS/R0 value as the gas concentration increases, indicating that the sensor resistance decreases as more gas is adsorbed onto the sensing material.

## Graphical Representation: Calibration Curves
The calibration curves for various gases can be plotted with RS/R0 on the y-axis and gas concentration on the x-axis (in logarithmic scale). These curves help interpret the sensor's output based on known concentrations of specific gases. The slopes of these curves vary for each gas due to differences in adsorption behavior, surface reactions, and gas sensitivity.

Example Graph:
CO2 Detection Curve:
At low concentrations (200-1000 ppm), the RS/R0 ratio is

z
