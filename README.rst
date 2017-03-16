
********************************************************
Adapting OV7670 camera module with Nexys4 DDR board
********************************************************

.. contents:: Table of Contents
   :depth: 2
   
Introduction 
=============
The project is done in Vivado 2016.3. A camera module OV7670 is addapted to the nexys4DDR board. The camera module is configured using I2C interface. The register configuration is preloaded in the FPGA. A simple BRAM is used on the FPGA is used to buffer the captured video data. The buffered data will then be sent to the VGA output and displayed on the monitor.

Vivado Design
=============




