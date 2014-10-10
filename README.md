# nagios-plugins-outports

## Overview
This nagios plugin is used to check the percentage of the free outgoing ports available on every network interface.

## Usage
You can set warning and critical tresholds like this:

    check_outports -w 35 -c 20

It would trigger CRITICAL alert if the percentage of the free outgoing ports is 20% or below. Also it would trigger the WARNING alert if the free percentage is lower than 35%, but not lower than 21%.
