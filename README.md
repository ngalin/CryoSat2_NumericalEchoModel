CryoSat2_NumericalEchoModel
===========================
DON'T HAVE GIT, AND WANT TO SEE THE PAPER? CLICK ON THE RIGHT HAND SIDE
BUTTONS: "CLONE IN DESKTOP" AND/OR "DOWNLOAD ZIP"
********************************************************************************************************
Copyright (c) 2013, Duncan J. Wingham,
Center for Polar Observation and Modelling,
University College London, London, U.K.
********************************************************************************************************
Mathematica code that computes the CryoSat-2 pulse-limited (PL), SAR and SARin echoes.
********************************************************************************************************
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
*********************************************************************************************************

Description: This code computes the CryoSat-2 pulse-limited, SAR and SARin echoes. 
No input from the user is required. Output files of the calculated model are generated
and written by this script. A usage example, which plots examples of the model output 
waveforms, is provided below. 

Please do familiarise yourself with the code, as certain segments of this code should be
modified depending of which echo HPL, SAR or SARin you would like to generate.

A detailed description of the theory on which this code is built:
"Precise Estimates of Ocean Surface Parameters from the CryoSat-2 Synthetic Aperture,
Interferometric Altimeter",
Katharine A. Giles, Duncan J. Wingham, Natalia Galin, Robert Cullen, Walter H. F. Smith.

This code consists of two parts:
Part1) Code to generate and write to disk the look-up tables for PL, SAR and SARin echoes.
Part2) Code to ingest the look-up tables generated in Part1, and demonstrate the use of 
           these look-up tables, providing example plots of SAR and PL echoes.
           
This code, the companion paper, and lookup tables for SAR and PL modes are available on
the GitHub repository: https://github.com/ngalin/CryoSat2_NumericalEchoModel