# Requirements

## Introduction
To design a system which calculates various electrical and electronics parameter for the user's ease.

## Research
### Cable
*	The conductor cross-section shall be chosen such that the conductor withstands prospective short circuit current for a specified duration of time.
*	Area of cross-section of the conductor shall be sized to carry estimated load current continuously such that the temperature rise of the conductor is within the acceptable limits for the installation conditions foreseen
*	Voltage drop within the cable is within the permissible limits so that the functionality of the connected load by the cable remains unaffected
### Series Circuit Analysis
*   A Circuit is a collection of interconnected components.
*   We asssume components to be linear in nature.
*   We will analyze Series circuit , based on input provided by user
*   We will be mainly focusing on Calculating Equivalent Impedance , Power factor etc.
### Source Transformation
*   Source transformation is a process of simplifying a circuit solution.
*   Here we transform voltage source in to current source and vice-verca.
*   Performing a source transformation consists of using Ohm's law.
### Star (Y) and Delta (Δ) Conversion
*   Star and Delta connections are the two types of connections in a 3-phase circuits.
*   The transformation is used to establish equivalence for networks with three terminals.
*   Where three elements terminate at a common node and none are sources, the node is eliminated by transforming the impedances.
*   It allows us to convert impedances connected together in a 3-phase configuration from one type of connection to another.
### Current Division
*   The current divider is a simple circuit that provides an output current that is a fraction of the input current
*   Current division is the splitting of current between branches of the divider
*   We use the current division rule to find the current in the branches
### Voltage Division
*   The voltage across a resistance is equal to the value of the ratio of resistance divided by equivalent 
*   This rule is used to determine the value of the voltage in a dividor circuit
### Equivalent Resistance, Capacitance and Inductance of Circuits
*   The equivalent resistance, capacitance and inductance of a circuit can be calculated by their equivalent formulas
*   Passive components in parallel and series circuits add up in ratios relating to their properties


### Resistor color code 
*   The resistor color code was developed during the year 1920. The color bands are printed on the body of tiny resistor components. Generally, for color code, we can use this resistor mnemonic called BBROY. This color-coding shortcut has an acronym for how to identify a resistor value.
*   The Carbon composition resistors have 3 to 6 resistor color bands. The 3-band resistor has three colors with multiplier and no tolerance.The three bands can be selected to know the resistor value. Whereas, the 4 band, 5 band, and 6 band resistors have an extra band known as tolerance.

### Circular Convolution using FFT
* Normal convolution between two signals can be described as sliding and multiplication of one of the signals reversed against the other signal.
* FFT is a fast algorithm for execution of DFT. The multiplication of two DFTs is equivalently a circular convolution of the two sequences. 
* We can make use of DFT for computation of convolution as the circular convolution in time domain is equivalently a multiplication in the DFT domain using a property of convolution. 
* We need to convert the linear convolution to a circular convolution and then make use of FFT algorithm to reduce the number of computation for filtering. 
* The procedure to convert the linear convolution to a circular convolution is increase length of each sequence by appending zeros so that it is equal to the length of the resulting convolved sequence. Then circularly convolve the resulting appended sequences

## Cost and Features

• The advantage of this project the the quickness in which the program works and no need to perform heavy calculation which will be taken care by the program

• A lot of time and money can be saved in this project as the result leads to quick installation and accurate results.

## Defining MY System
   
• The system will be getting some essential paramenters from the user and it will compute the values and with which it will be able to choose or design the product.
   
   ## SWOT ANALYSIS
   ![Off White and Black SWOT Analysis Chart (2)](https://user-images.githubusercontent.com/80444408/124426758-1b67a480-dd88-11eb-8dc8-3cfec9dff8d2.png)

  

   # 4W&#39;s and 1&#39;H

## Who:

• Intended for people who want to calculate current and Voltage Division, Equivalent Resistance, resistor color code, implementation of logic circuits and electrical and electronics parameters

## What:

• It provides you with quick calculation of electrical and electronics parameters


## When:

• When these electronic parameters are required in simple projects or lab work
## Where:

• Users can use this application on their desktop or laptop terminal

# Detail requirements
## High Level Requirements
| ID | Description | Status (Implemented/Future) |
| ---- | ----------- | --------------------------- |
| HA01 | Basic Circuit Solver | Implemented|
| HA02 | Cable Capacities | Implemented |
| HA03 | Voltage and Current Calculations | Implemented |
| HA04 | Passive Circuit Components Calculations | Implemented |
| HA05 | Calculating resistance based on color code | Implemented |
| HA06 | Calculating Circular Convolution | Implemented |
| HA07 | Calculation of Electronic formula | Implemented |




## Low level Requirements
| ID | Description |HLR|Status (Implemented/Future)| 
| ---- | ----------- | --------------------------- |-----------|
| LA01 | Finding Equivalent Impedance in Series RLC Circuit | HA01 |Implemented|
| LA02 | Finding Power Factor in Series RLC Circuit | HA01 |Implemented|
| LA03 | Star Delta Conversion | HA01 |Implemented|
| LA04 | Source Transformation | HA01 |Implemented|
| LA05 | Current Divsion Calculation |HA03| Implemented|
| LA06 | Voltage Divsion Calculation |HA03| Implemented|
| LA07 | Equivalent Parallel R,L,C  |HA04| Implemented|
| LA08 | Equivalent Series R,L,C  |HA04| Implemented|
| LA09 | Calculating Ampacity   |HA02| Implemented|
| LA10 | Calculating Voltage Drop   |HA02| Implemented|
| LA11 | Calculating Derating Factors | HA02|Implemented|
| LA12 | Calculation of Rasistance from the rasistor color band  | HA05|Implemented|
| LA13 | Calculating Current,Voltage,Rasistance,and other electronic formulas  | HA05|Implemented|
| LA14 | Inputting 2 discrete time signals |HA06| Implemented|
| LA15 | FFT Calculation for Input time signal as 4 | HA06 | Implemented|
| LA16 | FFT Calculation for Input time signal as 8 | HA06 | Implemented|
