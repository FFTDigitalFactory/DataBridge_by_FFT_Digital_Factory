## Overview

The FFT DataBridge connects edge devices in manufacturing with the Snowflake Cloud. It is specifically tailored for Siemens Industrial Edge and runs locally on the edge device. The app enables secure, configurable, and consistent transmission of production data to the cloud for analysis.

## Functionality

- Communicates with the locally installed FFT_DataService to retrieve standardized access to both real-time and historical data from IIH
  
- Supports variable-level filtering and configuration for writing to multiple tables and automatically
  fetches available variables from the FFT DataService
  
- Supports retrieval of historical data
  
- Freely configurable via IEM schema configurations, with an additional TOML-based configuration mode to extend advanced settings
   
## Security

The FFT DataBridge is built with security and reliability in mind:

- Southbound connection to Snowflake
  
- End-to-end TLS encryption
  
- Asymmetric authentication using encrypted key files (public/private key pair)

## Documentation
[User Manual – FFT DataBridge](UserManual_DataBridge_V002.pdf)
