
## NFV-Fault-Analytics-Basic
## Data
 Telemetry data contains parameters based on cpu usage, memory used etc fetched through OpNFV Barometer. Metrics from three different VNFs constituting a network service along with service level KPIs (key performance indicator) are given to perform NFV Fault Analytics.
  * KPI (key performance indicator) data is used to showcase anomaly detection.
  * Netfilter VNF data is used for accuracy comparison between compacted vs original data.
  * VNF (Netfilter, Shorewell, Snort) metrics  data is used with key performance indicator( "kpi_anomaly.csv") metrics For Cross Layer Fault Signatures detection.
  
## Notebook Walkthrough
  * Script is divided into four parts:
    1. Anomaly detection (DBScan and AutoEncoder are used)
    2. Accuracy comparison between compacted vs original data (Random Forest)
    3. Cross Layer Fault Signatures detection
    4. Spyder Chart visualization for parameters comparison
  

## Authors
 **Deepanshu Karnwal**

## Licence
 This Project is licenced under MIT Licence - see (LICENCE.md/ licence.md ) file for details.

