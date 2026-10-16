# HTTP-Traffic-Analysis

## Overview

The purpose of this investigation is to look at a HTTP request to a server, the response to the request by the server, and the visible information contained in unencrypted traffic.

## Scope and tools

Wireshark will be used to investigate the network traffic and to isolate the HTTP request and response from the server. The limitation within the investigation will be the use of the sample capture, HTTP.cap, provided by Wireshark.

## Methodology

First, the sample capture is loaded into Wireshark, all network traffic is captured and displayed as seen in Screenshots/Network-Capture-001.
As only HTTP traffic is needed, a HTTP display filter is added to isolate all HTTP traffic, as seen in Screenshots/Network-Capture-002. From here, the packets can be observed by selecting a packet and viewing the information contained within them.

## Evidence and observations
