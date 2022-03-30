# NI-DAQmx-Tutorial

## 0. Information: 

**Author:** National Instruments

* The **nidaqmx** package contains an API (Application Programming Interface) for interacting with the NI-DAQmx driver.

* The package is implemented as a complex, highly object-oriented wrapper around the NI-DAQmx C API using the [ctypes](https://docs.python.org/2/library/ctypes.html) Python library.
* **nidaqmx** supports CPython 3.7+ and PyPy3.

* [ni.com/downloads](http://www.ni.com/downloads/) to upgrade your version of NI-DAQmx.

* [NI Hardware and Operating System Compatibility](https://www.ni.com/r/hw-support) for which versions of the driver support your hardware on a given operating system.( Win and Linux )
* https://www.ni.com/documentation/en/ni-daqmx/20.1/manual/manual-overview/ ( Given by Sen Yang )

* https://nidaqmx-python.readthedocs.io/en/latest/ NI-DAQmx Python Documentation

* https://wiki.freepascal.org/NI-DAQmx_and_NI-DAQmx_Base_examples example of NI-DAQmx

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



## 3. **API Reference:**

* nidaqmx.constants
* nidaqmx.errors
* nidaqmx.scale
* nidaqmx.stream_readers
* nidaqmx.stream_writers
* nidaqmx.system
  * nidaqmx.system.collection
    * nidaqmx.system.device_collection
    * nidaqmx.system.persisted_channel_collection
    * nidaqmx.system.persisted_scale_collection
    * nidaqmx.system.physical_channel_collection
  * nidaqmx.system.device
  * nidaqmx.system.physical_channel
  * nidaqmx.system.storage
    * nidaqmx.system.persisted_channel
    * nidaqmx.system.persisted_scale
    * nidaqmx.system.persisted_task
  * nidaqmx.system.watchdog
    * nidaqmx.system.expiration_state
    * nidaqmx.system.expiration_state_collection
* nidaqmx.task
  * nidaqmx.task.channel
    * nidaqmx.task.ai_channel
    * nidaqmx.task.ao_channel
    * nidaqmx.task.ci_channel
    * nidaqmx.task.co_channel
    * nidaqmx.task.di_channel
    * nidaqmx.task.do_channel
  * nidaqmx.task.channel_collection
    * nidaqmx.task.ai_channel_collection
    * nidaqmx.task.ao_channel_collection
    * nidaqmx.task.ci_channel_collection
    * nidaqmx.task.co_channel_collection
    * nidaqmx.task.di_channel_collection
    * nidaqmx.task.do_channel_collection
  * nidaqmx.task.export_signals
  * nidaqmx.task.in_stream
  * nidaqmx.task.out_stream
  * nidaqmx.task.timing
  * nidaqmx.task.triggers
    * nidaqmx.task.arm_start_trigger
    * nidaqmx.task.handshake_trigger
    * nidaqmx.task.pause_trigger
    * nidaqmx.task.reference_trigger
    * nidaqmx.task.start_trigger
* nidaqmx.types
* nidaqmx.untils
