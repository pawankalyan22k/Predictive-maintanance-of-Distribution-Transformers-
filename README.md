# Predictive-maintanance-of-Distribution-Transformers-


1. Data Description
   
The dataset consists in two archives in Excel: \n
(i) Dataset_Year_2019.xlsx   \n
(ii) Dataset_Year_2020.xlsx   \n

Each file has 16 columns with the information of characteristics of distribution transformers at Cauca Department during 2019 and 2020 years, columns in order ascendent are:   \n
A.Location: Binary variable that indicates the area in which the transformer is located: 1 if it is urban and 0 if it is rural. \n
B.Power: Transformer capacity in [kVA]. For transformers immersed in oil the standard IEC 76-1 eestablishes normal service conditions as altitude above sea level no higher than 1000 [m] and room temperature higher than and less than . \n
C.Self-protection: Binary variable that indicates if the transformer has a switch internally for low voltage protection: 1 if it is self-protected and 0 if it is not. \n
D.Average earth discharge density DDT: Variable in is defined as the average number of lightning strikes per square kilometer in a year. \n
E. Maximum ground discharge density DDT: Variable in is defined as the maximum number of lightning strikes per square kilometer in a year. \n
F. Burning rate: Variable based on the reliability of the system and calculated from the failure events recorded in the years of study. It is defined as the number of failures of a component per unit of recording time. \n
(1)
G. Criticality according to previous study for ceramics level: Binary variable product of the result of a previous study carried out for the distribution company by third parties: 1 if due to its geographical location it is at high risk and 0 otherwise, it does not present high risk. \n
H.Removable connectors: Binary variable that indicates if the transformer installation has removable medium voltage connectors to carry out interventions without the need to open from the disconnector immediately upstream: 1 if it has the removable connectors installed and 0 if it does not. \n
I.Type of clients: Categorical variable that indicates whether the transformer mainly feeds stratum 1, 2, 3, 4, 5, 6, commercial, industrial or official residential users. \n
J.Number of users: Integer variable that indicates how many customers the transformer in question is supplying the electric power service. \n
K.Electric power not supplied EENS: Variable based on the risk involved in the failure, represents the [kWh] that the distribution company stops selling when the transformer stops operating due to a failure event. \n
L.Type of installation: Categorical variable that indicates whether the installed transformer is in a cabin, in a H-type structure, if it has a macro with an anti-fraud net, if it is a pad mounted type, if it is in a simple pole-type structure, an anti-fraud net pole, a metal tower or others. \n
M.Air network: Binary variable that indicates whether the transformers low voltage network is of the aerial type: 1 if it is indeed and 0 otherwise. \n
N.Circuit Queue: Binary variable that indicates if the transformer is located within the medium voltage network at a terminal point of the circuit: 1 if it is in the queue and 0 if it is in a passing point. \n
O.km of network LT: Continuous variable that corresponds to the length in [km] of the low voltage transformer. \n
P. Burned transformers: Binary variable that indicates if the transformer has been burned during this year: 1 if it is burned and 0 otherwise. \n
