# ASPAM
Installation for animal spontaneous activity monitoring

The project include three main part:
* the rat box with the wheel (main ASPAM unit)
* the ADC for N channels
* the web-interface controlling logging 

All these part develops independently and, thus, are decorated as submodules.

# Submodules (parts of the project)

* **TCC** - the electronic circuit of the Turn Counter Controller (TCC) board

* **wheelbox** - mechanical drawings for manufacturing rat box and the wheel.  
We have a nice [video of this setup on YouTube](https://youtu.be/OO7PnywRuvI).

# Submodules (independent projects)

* **TCC_firmware** - firmware for SMT32 mounted to the TCC board

* **webinterface** - WSGI web interface for plotting rat running data

# Citation

- Borzykh A.A., Gaynullina D.K., Shvetsova A.A., et al. (2022) Voluntary wheel exercise training affects locomotor muscle, but not the diaphragm in the rat. *Front. Physiol.* **13**:1003073. doi: [10.3389/fphys.2022.1003073](https://dx.doi.org/10.3389/fphys.2022.1003073)
- Borzykh, A.A., Selivanova, E.K., Shvetsova, A.A. et al. (2020) Changes in the Expression of Genes Regulating Calcium Homeostasis in Rat Myocardium Induced by Voluntary Wheel Training: The Role of Thyroid Hormones. *Biochem. Moscow Suppl. Ser. A* **14**, 67–73. doi: [10.1134/S1990747820010043](https://doi.org/10.1134/S1990747820010043)
- [Rus] Borzykh A.A., Kuzmin I.V., Kiryukhina O.O., et al. (2020) VOLUNTARY RUNNING TRAINING OF FEMALE RATS DURING GESTATION: CHARACTERISTICS OF AN EXPERIMENTAL MODEL. *Aviaspace and ecological medicine* **54**:2, 89-95. doi: [10.21687/0233-528X-2020-54-2-89-95](https://doi.org/10.21687/0233-528X-2020-54-2-89-95)
- [Rus] Borzykh A.A., Kuzmin I.V., Nesterenko A.M., et al. (2017) DYNAMICS OF RATS'' VOLUNTARY RUN CHARACTERISTICS FOLLOWING 8 WEEKS OF TRAINING. *Aviaspace and ecological medicine* **51**:3, 66-73. doi: [10.21687/0233-528X-2017-51-3-66-73](https://doi.org/10.21687/0233-528X-2017-51-3-66-73)

# Licensing 

The project "Automated Spontaneous Physical Activity Monitoring" 
(A. Nesterenko @comcon1, I. Kuzmin @kuzmin-ilya, P. Mamonov @pmamonov)  
is released under  license CC BY-SA 3.0.

Submodules listed as independent projects are not part of this project and 
are released under their own licenses.
