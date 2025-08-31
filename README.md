# This repository provides access to data collected for a multi-objective vehicle routing problem study
This dataset contains parameters used in a multi-objective optimization study of a vehicle routing problem (VRP) that seeks to minimize logistics costs, greenhouse gas emissions, and accident risks. The study is based on a real-world scenario of a hypothetical retail company with a central warehouse in the state of São Paulo, Brazil. The company’s fleet must deliver goods to stores located in nearby cities.

In addition to road distances, the dataset provides inputs for estimating accident risk costs, calculated using the statistical methodology of Bilato et al. (2023) with Monte Carlo simulation.

The database consists of the following files:

- arc_description.xlsx – Defines the arcs of the routing problem, specifying the roads included in each arc and their corresponding travel distances. Each road has a unique code, and Sheet 1 lists the roads that compose each arc.
- CNT_data.xlsx – Contains accident risk factors associated with road characteristics. For example, it shows that Single-lane two-way road present higher fatality risks. Data were obtained from the National Transport Confederation (CNT).
- DER-SP_data.xlsx – Provides additional road information, including characteristics and heavy vehicle flows for all roads in the problem instance. Data were sourced from the Department of Roads and Highways of the State of São Paulo (DER-SP).
- Distances.xlsx – Contains the road distances between arcs, as obtained from Google Maps.
- Risk_calculated.xlsx – Presents the estimated accident risk costs for each arc, derived using the methodology of Bilato et al. (2023) and Monte Carlo simulation.

Reference
Bilato, G. A.; Rocco, C. D.; Azevedo, A. T. Bi-objective approaches to deal with accident risk and logistic costs in vehicle routing problems. Pesquisa Operacional, 2023.
