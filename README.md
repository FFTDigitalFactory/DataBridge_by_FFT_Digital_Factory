## Overview

The DataBridge connects edge devices in manufacturing with the Snowflake Cloud. It is specifically tailored for **Siemens Industrial Edge** and runs locally on the edge device. The app enables secure, configurable, and consistent transmission of production data to the cloud for analysis.

## Functionality

- **Southbound connector** with TLS encryption and asymmetric authentication (public/private key)
- Connects to a **custom-developed data service** on the edge device
- Reads defined **attributes**, which are configured directly in the field on the edge
- Data transformation into defined tables is handled automatically via a **Snowflake pipeline**
- Supports **retrieval of historical data**, depending on edge device capacity
- Maintains a **write log** with start and end timestamps to ensure consistent data transmission
- After a container crash, the write log is reused to prevent data loss
- Freely configurable via **IEM schema configurations**

## Security

- **End-to-end TLS encryption**
- **Asymmetric authentication** using encrypted key files (public/private key pair)
- Stored keys are **password-protected**

## Documentation
[User Manual – DataBridge (V002)](UserManual_DataBridge_V002.pdf)
