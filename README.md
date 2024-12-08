# CAMMU
CAMMU is a universal multi material filament system, inspired by ERCF and Tradrack systems but designed to use no servo at all and keep components as accessible as possible.

A full custome controller and DIY controller is currently in the works and to be released soon. 2 stepper ports and 6 endstop connections are all that is needed if you build the 4 gate version.

Please feel free to contribute towards future projects and developments

### Updates
- 05-12-2024:
  - Add in basic instructions for assembly
- 08-12-2024:
  - Added Build FAQ below 

### Build FAQ
- For the software control aspect of CAMMU, we decided to not reinvent the wheel and make use of the fantastic existing software called **Happy Hare** by moggieuk. You can find his github page [***HERE***](https://github.com/moggieuk)
  - You are requied to [***install Happy Hare***](https://github.com/moggieuk/Happy-Hare/wiki/Installation) on your existing klipper installation.
  - In due time we will compile a short guide on the installation and configuration of **Happy Hare**
- For the sensing aspect, not only do you require a filament sensor per gate, but also require a filament sensor on your toolhead
  - If you currently use the Sherpa range:
    - You can find a fantastic toolhead sensor for [***Sherpa Mini***](https://github.com/v6cl/MyDIYthings/tree/main/3Dprinters/AnnexEngineeringMOD/SherpaMini/SherpaMiniFilamentSensor).
      - This is a fantastic toolhead sensor and can easily be wired up to your existing toolhead board if you have one.
  - You also require a filament cutter on your toolhead as
    - The one we recommend and have tested can be found on Prusa Printables [***HERE***](https://www.printables.com/model/622289-filament-cutter-for-sherpa-and-sherpa-patterned-ex/files)
