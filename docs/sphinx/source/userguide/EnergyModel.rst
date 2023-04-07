EnergyModel
===========
An instance of EnergyModel contains energy predictions and information about the model assumptions and information sources.

Summary Elements include:
* EnergyModelID - Unique identifier that represents the specific instance of the EnergyModel.
* EnergyModelName -Type of design/energy production model for the PV system which could be Pvsyst, SAM, PV Watts, or Other.
* ModelRunDate - The date and time associated with the energy model run.

Detailed Elements include:
* EnergyModelInput: This object represents the data input into an energy model.
* * CapacityAC: The value of the CapacityAC applied within the model.
* * CapacityDC: The value of the CapacityDC applied within the model.
* * FileFolderURL: Use this element to pass the data's source document.

* EnergyModelOutput
* * EnergyACAnnual: Annual level of generated AC Energy.
* * EnergyACAnnualP50: Average level of generation, where the output is forecasted to be exceeded 50% over the projects life as determined by the model.
* * EnergyACAnnualP90: Average level of generation that is predicted to be exceeded 90% of the projects life as determined by the model.
* * EnergyACModeled:
