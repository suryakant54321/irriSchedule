# irriSchedule
Python Flask based web application for crop water management.

- Python based web application for agro-meteorological data visulization.
- Sensor data visulization and processing for Reference, crop Evapotranspiration (ET) and irrigation scheduling. 
- Integrates SOS parsers using [Telegram-Bot-Scripts] to [python-telegram-bot]. More information about [Telegram Bot Platform].
- Added working use case for [IWC project].

### Version
0.0.1

### Depends on

Only tested in Ubuntu 15.10 with python 2.7

- xmltodict
- requests
- dateutil.parser
- colorama 
- pandas
- [PCSE]
- [Python-SOS-Client]

### Other References

- [PCSE] Python Crop Simulation Environment 
- [SWAP] Soil Water Atmosphere Plant
- [Hydrus-1D] Hydrus 1D

### Contains

1. Folder: src

### Advantages

	1. Python based 

### Limitations

	1. SOS response parsers.
	
### Installation

A. Download

- Clone from GitHub

```sh
$ git clone https://github.com/suryakant54321/irriSchedule 
```

- Install dependencies 

```sh
$ cd irriSchedule
$ pip install -r requirements.txt 
```

B. Usage of irriSchedule

	Add to environment path
	or
	Just import the required workflow
<!--

```sh
$ python
>>> import moduleName
>>> help(moduleName)
```
-->

C. Other Crop Simulation Environment

- [SWAP] Soil Water Plant Atmosphere framework.
- [Hydrus-1D] a public domain Windows-based modeling environment for analysis of water flow and solute transport in variably saturated porous media. Designed by [pc-progress].
- [WOFOST] (WOrld FOod STudies) is a simulation model for the quantitative analysis of the growth and production of annual field crops.
- [APSIM] The Agricultural Production Systems sIMulator (APSIM) a highly advanced simulator of agricultural systems.

<!--
#### Snapshots


![Snapshot 1]()


![Snapshot 2]()


![Snapshot 3]()

-->
#### TODO

1. Add web application layout
2. Add irrigation scheduling component
3. Write detailed documentation using [Sphinix].


[OGC]: <http://www.opengeospatial.org/>
[SOS]: <http://www.opengeospatial.org/standards/sos>
[PHP-istSOS-client]: <https://github.com/suryakant54321/php_istSOS_client>
[sos4R]: <https://github.com/52North/sos4R>
[Sphinix]: <http://www.sphinx-doc.org/en/stable/>
[Telegram Bot Platform]: <https://telegram.org/blog/bot-revolution>
[Telegram-Bot-Scripts]: <https://github.com/suryakant54321/Telegram-Bot-Scripts>
[python-telegram-bot]: <https://github.com/python-telegram-bot/python-telegram-bot>
[IWC project]: <http://itra.medialabasia.in/?p=623>
[Python-SOS-Client]: <https://github.com/suryakant54321/Python-SOS-Client>
[PCSE]:<http://pcse.readthedocs.io/en/stable/index.html>
[SWAP]:<http://www.swap.alterra.nl/>
[Hydrus-1D]:<http://www.pc-progress.com/en/Default.aspx?h1d-library>
[pc-progress]:<http://www.pc-progress.com/en/>
[WOFOST]:<http://www.wageningenur.nl/en/Expertise-Services/Research-Institutes/alterra/Facilities-Products/Software-and-models/WOFOST.htm>
[APSIM]:<https://www.apsim.info/>


