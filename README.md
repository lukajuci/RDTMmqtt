## Overview

This repository contains the node-red flow used to route incoming data packets from the gateway to a csv file located on the user device which can then be used by the data visualization software

The flow is a modified version of what is found in **[this tutorial](https://meshtastic.org/docs/software/integrations/mqtt/nodered/)** in the Meshtastic documentation. It is currently incomplete as it can process the incoming MQTT protobuf but decoding the RDTMmetrics protobuf nested within is incomplete
