# ASPAM
Installation for animal spontaneous activity monitoring

The project include three main part:
* the rat box with the wheel (main ASPAM unit)
* the ADC for N channels
* the web-interface controlling logging 

All these part develops independently and, thus, are decorated as submodules.

# Submodules

* **ADC** - the electronic circuit of the ADC board

* **ADC_firmware** - firmware for SMT32 mounted to the ADC board

* **wheelbox** - mechanical drawings for manufacturing rat box and the wheel

* **webinterface** - WSGI web interface for plotting rat running data

# Licensing 

The project "Automated Spontaneous Physical Activity Monitoring" 
(A. Nesterenko, I. Kuzmin, P. Mamonov)  
is released under  license CC BY-SA 3.0.
