## Overview

The FFT_DataBridge connects edge devices in manufacturing with the Snowflake Cloud. It is specifically tailored for Siemens Industrial Edge and runs locally on the edge device. The app enables secure, configurable, and consistent transmission of production data to the cloud for analysis.

## Functionality

- Southbound connector with TLS encryption and asymmetric authentication (public/private key)
- Connects to the local FFT_DataService to retrieve secure and standardized access to both real-time and historical data from IIH
- Supports variable-level filtering and configuration for writing to multiple tables
- Supports retrieval of historical data, depending on the edge device capacity
- Freely configurable via IEM schema configurations, with an additional TOML-based configuration mode to extend advanced settings
   
## Security

- End-to-end TLS encryption
- Asymmetric authentication using encrypted key files (public/private key pair)

## Documentation
[User Manual – DataBridge](UserManual_DataBridge_V002.pdf)
