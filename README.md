# PAMELA: imPedAnce-based shM with tEmperature fLuctuAtions

To download the dataset of the benchmark PAMELA, please fill the form:

__________________________________________________________________________________________________
# Description

PAMELA is a dataset of PZT measurements of impedance-based SHM with temperature fluctuations in healthy and damaged conditions. This experiment was conducted at SHM Lab UNESP/Ilha Solteira.

The experimental setup for measuring electromechanical impedance in a thermal chamber is presented below. 

<img src="setup1.jpg " width="60%">

<img src="setup2.jpg " width="60%">

An aluminum beam with a dimension of  500 mm x 40 mm x 2 mm of length, width, and thickness, respectively, is utilized in the tests. A PZT buzzer from Murata (number 7BB-35-3) with a diameter of 25 mm and thickness of 0.23 mm, with a base plate of brass, is bonded to the surface of the beam, as seen in the setup. The beam is tested in a free-free condition with elastic straps inside a thermal chamber. 

The structural modification to simulate possible damages is a sheer mass add by a clip or cuts with different deep. Four conditions are described as represented by damage D1, D2, D3, and D4, as explained in the figure below.

<img src="damages.jpg " width="70%">

The impedance signature is estimated accurately using a LabVIEW software with a National Instruments DAQ device, model USB-6211 data acquisition system with 16 bits and a sampling rate of 250 kHz. A chirp signal with  1 V peak-to-peak in the range of frequency from 0 to 125 kHz is applied. An electric circuit adequately conditions the voltage and current. All details about the instrumentation and identification of the impedance signals used here can be found in the reference papers listed below for attentive readers.

Six sets of measurements in different temperatures are performed in the baseline and damage conditions. These temperatures are 24ºC, 40ºC, 55ºC, 70ªC, 85ºC, and 100ºC, controlled in a thermal chamber used in the test campaign. The data files have two folders with undamaged and damaged states with the real and imaginary impedance signatures measured and previously estimated.

__________________________________________________________________________________________________
# Authors

  <li>Samuel da Silva (UNESP) </li>
  <li>Marcos Omori Yano (UNESP) </li>
  <li>Camila Gianini Gonsalez-Bueno (UNESP) </li>
  
__________________________________________________________________________________________________
# How to cite

The data are still available for non-commercial research under the following terms: (i) the SHM Lab at UNESP/Ilha Solteira should be acknowledged as the source of the data; (ii) in publications, relevant publications by members of the SHM Lab at UNESP/Ilha Solteira should be cited; (iii) this benchmark should be cited as PAMELA.

This dataset was used in this publication:

<li>da Silva S, Yano M O, Gonsalez-Bueno, C G. Transfer Component Analysis for Compensation of Temperature Effects on the
Impedance-Based Structural Health Monitoring. Journal of Nondestructive Evaluation. 2021;</li><br>

<li>Gonsalez-Bueno C G, da Silva S, Abreu G L C M, Baptista F G, Lopes Jr, V.  Yano M O, Gonsalez-Bueno, C G. Fuzzy Clustering to Distinguish Structural Damage from Temperature Effect. In: 11th Pan-American Congress of Applied Mechanics (PACAM XI), Foz do Iguçu (Brazil), 2010.</li><br>

If you are using a LaTeX Editor, you can cite the papers above using these BibTeX citations:

```
@article{TCA,
author = {Samuel da Silva and Marcus Omori Yano and Camila G. Gonsalez-Bueno},
title = {On the detection of a nonlinear damage in an uncertain nonlinear beam using stochastic Volterra series},
journal = {Journal of Nondestructive Evaluation},
volume = {0},
number = {0},
pages = {0},
year = {2021},
doi = {to appear},
URL = { to appear},
}

@inproceedings{PACAM,
author = {Camila G. Gonsalez-Bueno and Samuel da Silva and Gustavo Abreu and Fabricio Baptista and Vicente Lopes Jr}, 
title = {Fuzzy Clustering to Distinguish Structural Damage from Temperature Effect}
booktitle = {11th Pan-American Congress of Applied Mechanics (PACAM XI)},
location = {Foz do Iguaçu, PR, Brazil},
eventdate = {january 2010},
year = {2010},
}
```
__________________________________________________________________________________________________
# License

<img src="licenca.png" width="10%">
Creative Commons Attribution-NonCommercial-ShareAlike (CC-BY-NC-SA):

A creative commons license that bans commercial use and requires you to release any modified works under this license.

__________________________________________________________________________________________________
# Funding

São Paulo Research Foundation (<a href="http://www.fapesp.br">FAPESP</a>), grant numbers 15/25676-2 and 17/24977-4, Brazilian National Council for Scientific and Technological Development (<a href="http://www.cnpq.br/">CNPq</a>), grant number 306526/2019-0, and Brazilian Coordination for the Improvement of Higher Education Personnel (<a href="https://www.gov.br">CAPES</a>)-Finance Code 001 funded this experimental setup.

<img src="sponsors.jpg " width="50%">


