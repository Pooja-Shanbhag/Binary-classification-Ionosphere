# Ionosphere - Binary Classification


The purpose of this project is to predict whether there is a structure in the atmosphere or not given radar returns.

Dataset: Ionosphere Data Set : https://archive.ics.uci.edu/ml/datasets/Ionosphere.
Information: https://archive.ics.uci.edu/ml/machine-learning-databases/ionosphere/ionosphere.names.
This radar data was collected by a system in Goose Bay, Labrador.  This
system consists of a phased array of 16 high-frequency antennas with a
total transmitted power on the order of 6.4 kilowatts.  See the paper
for more details.  The targets were free electrons in the ionosphere.
"Good" radar returns are those showing evidence of some type of structure 
in the ionosphere.  "Bad" returns are those that do not; their signals pass
through the ionosphere.  

Received signals were processed using an autocorrelation function whose
arguments are the time of a pulse and the pulse number.  There were 17
pulse numbers for the Goose Bay system.  Instances in this databse are
described by 2 attributes per pulse number, corresponding to the complex
values returned by the function resulting from the complex electromagnetic
signal.
