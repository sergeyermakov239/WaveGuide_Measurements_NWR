# WaveGuide Measurements, Nicolson-Ross-Weir Method
A function for extracting material parameters from S-parameters measurements is implemented, basing on a stepwise NRW method ([link](https://www.researchgate.net/publication/254018808_A_Stepwise_Nicolson-Ross-Weir-Based_Material_Parameter_Extraction_Method))

- The main file is Matlab Live Script `right_measurements.mlx`
- To extract material parameters from your measurements you need to apply function **read_data_phase_corr()**\
   to `.s2p` files with S-parameters
- Geometry of the experiment and several examples are also included in Live Script

> [!NOTE]
> An implementation of NRW method in the attached article ([link](https://www.researchgate.net/publication/254018808_A_Stepwise_Nicolson-Ross-Weir-Based_Material_Parameter_Extraction_Method)) overcomes some difficulties, where standart NRW method fails, for example fabry-perot resonanses in the investigated material
