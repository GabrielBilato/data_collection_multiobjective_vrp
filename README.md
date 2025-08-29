# This repository provides access to data collected for a multi-objective vehicle routing problem study
The study develops a mathematical model for vehicle routing in a company seeking to minimize logistics costs, greenhouse gas emissions, and accident risks. The problem considers a heterogeneous fleet of vehicles with different fuel types and routes characterized by varying accident risks due to highway infrastructure. Accordingly, this repository provides access to data not included in the paper manuscript. As descrições de cada arquivo acima, estão explicadas abaixo:

- arc_description.xlsx: This database specifies the roads that form each arc of the problem, along with the corresponding travel distance. Each road is assigned a unique code, and sheet 1 details the roads included in each arc. This information is essential for determining the cost-risks associated with each arc;
- CNT_data.xlsx: This data will be essential for assessing accident risks in relation to road characteristics. For instance, it shows that single-lane two-way road carry a higher risk, as they are associated with elevated fatality rates. This information were obtained from National Transport Confederation (CNT) (https://cnt.org.br/acidentes-rodoviarios-caminhoes);
- DER-SP_data.xlsx: This data will be also essential for assessing accident risks as it contains informations related characteristics and heavy vehicle flows of all roads of the problem. This information were obtained from Department of Roads and Highways of the State of Sao Paulo (DER-SP) (www.der.sp.gov.br/WebSite/MalhaRodoviaria/PesquisaRodovias.aspx);
- Distances.xlsx: The distances of each arc were obtained from google maps;
- Risk_calculated.xlsx: The risk costs of each arc is presented in this document. These costs were estimated using the statistical approach from the Bilato et al. (2023) and Monte Carlo simulation.

Reference:
Bilato, G. A.; Rocco, C. D.; Azevedo, A. T. BI-OBJECTIVE APPROACHES TO DEAL WITH ACCIDENT RISK AND LOGISTIC COSTS IN VEHICLE ROUTING PROBLEMS, Pesquisa Operacional, 2023.
