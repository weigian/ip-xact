# ip-xact

```
# for linux/wsl
# get python venv ready 
sudo apt install python3
sudo apt install pip                                                                                                                                                              pip install virtualenv

# install peakrdl to venv
virtualenv venv-peakrdl
. venv-peakrdl/bin/activate
python3 -m pip install peakrdl

# test runs                                                                                                                                                                      peakrdl regblock atxmega_spi.rdl -o regblock/ --cpuif axi4-lite                                                                                                                  peakrdl regblock atxmega_spi.rdl -o regblock/ --cpuif apb3                                                                                                                       peakrdl regblock atxmega_spi.rdl -o regblock/ --cpuif passthrough                                                                                                                peakrdl c-header atxmega_spi.rdl -o atxmega_spi.h --testcase                                                                                                                     peakrdl html atxmega_spi.rdl -o html/

```
