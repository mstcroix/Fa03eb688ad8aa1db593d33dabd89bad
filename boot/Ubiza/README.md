# Boot
## Tata Ubiza 🌞
Native: inline assembler, implemented in C, extended in python
Generic:
Open: 
Redundant:
Robust (resilent): 
Self confinament: see CAN
Mesh: Hive
Polisystem:
RAM/ROM effective: Memory & Footprint 
Distributed File System: non-encrypted, pseudo-code

T_UNLnGNU - Tata Ubiza not Linux nor GNU nor UN*X, UNL for short


## Polisystem
### What is a collaborative Poli-space and Poli Operating System (Polisystem)?

https://www.thingsquare.com/blog/articles/why-iot-mesh/

### /proc/boot/sunshine
>Good morning sunshine

https://dunkels.com/adam/iot-challenges/

"At Thingsquare, we use a lightweight technique to collect crash reports from devices:

    For every build that is uploaded to devices, the ELF binary is stored and tagged with the git commit ID for that build.
    If a device crashes, the program counter at the time of the crash is stored in non-volatile memory.
    When the device reboots after the crash, the commit ID and program counter at the crash site is reported to the backend."

#### Crash re-synch strategy
nodes are exact copies
<pre>pseudo-code
    :on_crash
        mve pc, ubiza state    ;load program counter with current sol position
</pre>
at boot time, if a crash is detected, the last known valid state is recover, synchronised (as in blockchain) and continue from it.
Handling the whole as a SoS makes possible to update the 


#### Collaborative protocol with natural (organic) pseudo-encryption

see w3eb and w3iki

### Footprint

### Energy consumption
| Sunshine hours per day | Germany | Mexico | kWatts per/hour |
|- |- |- |- |
|  | 4.7	| 7.5 | |

https://www.worlddata.info/country-comparison.php?country1=DEU&country2=MEX

### Wireless technology


## References

### Hardware
#### Development boards
##### Silicon Labs
- Silicon Labs EFM32 and EFR32 devices!
https://www.silabs.com/developers/micrium-os
 
##### AVR

#### Arduino
https://www.arduino.cc/en/about

#### RaspberryPi
[https://www.raspberrypi.org/](https://www.raspberrypi.org/about/)

Raspberry Pi Foundation: Empowering young people to use computing technologies to shape the world

#### CircuitPython
https://circuitpython.org/

### RTOS
#### OSEK
#### FreeRTOS
#### uC/OS 
https://github.com/weston-embedded/uC-OS3
##### Safety Critial 
The Flexible Safety RTOS™ is a real-time operating system that has been pre-certified to key industry standards for functional safety. Powered by Micrium's field-proven and highly reliable μC/OS-II kernel, the Flexible Safety RTOS is suitable for applications that need to comply with any of the following safety standards: ISO 26262, IEC 61508, IEC 62304, EN 50128. Certification services are also provided for DO-178.
- https://weston-embedded.com/products/flexible-safety-rtos
- https://www.analog.com/media/en/dsp-documentation/software-manuals/Micrium-uCOS-III-UsersManual.pdf
<pre>
 OSSafetyCritialStart()
   Stack size analysis 1.5 to 2x
   MISRA rule set
</pre>
#### pyRTOS
RTOS written in pure Python, designed for use with CircuitPython


### OS
#### File Systems
- https://www.geeksforgeeks.org/unix-file-system/

### Programming languages
#### Assembler, inline assembler
#### Forth
#### C
#### Python
https://ruvi-d.medium.com/understanding-python-for-embedded-systems-developers-2a3310885d13
https://realpython.com/python-gil/
#### EVM Solidity
https://ethereum.org/en/developers/docs/programming-languages/python/
https://github.com/ethereum/py-evm
https://tradingstrategy.ai/blog/the-state-of-python-in-blockchain-in-2023
https://snakecharmers.ethereum.org/a-developers-guide-to-ethereum-pt-1/

### Energy
https://www.worlddata.info/country-comparison.php?country1=DEU&country2=MEX
