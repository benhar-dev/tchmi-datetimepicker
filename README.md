# Example DateTimePicker

## Disclaimer

This is a personal guide not a peer reviewed journal or a sponsored publication. We make
no representations as to accuracy, completeness, correctness, suitability, or validity of any
information and will not be liable for any errors, omissions, or delays in this information or any
losses injuries, or damages arising from its display or use. All information is provided on an as
is basis. It is the reader’s responsibility to verify their own facts.

The views and opinions expressed in this guide are those of the authors and do not
necessarily reflect the official policy or position of any other agency, organization, employer or
company. Assumptions made in the analysis are not reflective of the position of any entity
other than the author(s) and, since we are critically thinking human beings, these views are
always subject to change, revision, and rethinking at any time. Please do not hold us to them
in perpetuity.

## Overview 

Demo of creating a DateTimePicker from a TrendGraph.

## Install 

Not required.  Simply open the project.

You will find the CSS styling located in a HTML host inside the user control.  The Javascript is in an event under the main usercontrol item.

To use the PLC code to change the date/time of the system, simply link all parts of the GVL_HMI.systemTime to the DateTimePicker User control.  The system date will be changed as soon as a selection is made. 

## TwinCAT
This project uses TcXaeShell 3.1.4024.7 and TwinCAT HMI 1.10.1336.340

## Getting started
This is not a guide for TcXaeShell, please visit http://beckhoff.com/ for further guides
* Open the included TwinCAT project and activate on your local machine
* Login and set the PLC running
* Open the HMI in live view

