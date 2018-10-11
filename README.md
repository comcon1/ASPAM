# ASPAM
Installation for animal spontaneous activity monitoring

The project include three main part:
* the rat box with the wheel (main ASPAM unit)
* the ADC for N channels
* the web-interface controlling logging 

All these part develops independently and, thus, are decorated as submodules.

# Submodules (parts of the project)

* **TCC** - the electronic circuit of the Turn Counter Controller (TCC) board

* **wheelbox** - mechanical drawings for manufacturing rat box and the wheel

# Submodules (independent projects)

* **TCC_firmware** - firmware for SMT32 mounted to the TCC board

* **webinterface** - WSGI web interface for plotting rat running data

# Licensing 

The project "Automated Spontaneous Physical Activity Monitoring" 
(A. Nesterenko, I. Kuzmin, P. Mamonov)  
is released under  license CC BY-SA 3.0.

Submodules listed as independent projects are not part of this project and 
are released under their own licenses.
