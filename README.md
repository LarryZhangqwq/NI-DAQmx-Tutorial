# NI-DAQmx-Tutorial

## 0. Information: 

**Author:** National Instruments

* The **nidaqmx** package contains an API (Application Programming Interface) for interacting with the NI-DAQmx driver.

* The package is implemented as a complex, highly object-oriented wrapper around the NI-DAQmx C API using the [ctypes](https://docs.python.org/2/library/ctypes.html) Python library.
* **nidaqmx** supports CPython 3.7+ and PyPy3.

* [ni.com/downloads](http://www.ni.com/downloads/) to upgrade your version of NI-DAQmx.

* [NI Hardware and Operating System Compatibility](https://www.ni.com/r/hw-support) for which versions of the driver support your hardware on a given operating system.( Win and Linux )
* https://www.ni.com/documentation/en/ni-daqmx/20.1/manual/manual-overview/ ( Given by Sen Yang )

## 1. Installation

* Running **nidaqmx** requires NI-DAQmx or NI-DAQmx Runtime.

* [ni.com/downloads](http://www.ni.com/downloads/) to download the latest version of NI-DAQmx.

* Can also be installed **nidaqmx** with pip:

  ````
  $ python -m pip install nidaqmx
  ````

* The versions of the **nidaqmx**, numpy, six and enum34 packages used:

  ````
  $ python -m pip list
  ````

## 2. Additional Documentation 

* Refer to the [NI-DAQmx Help](http://digital.ni.com/express.nsf/bycode/exagg4) for API-agnostic information about NI-DAQmx or measurement concepts.

