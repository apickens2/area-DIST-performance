# Land cover change assessment for 2023

## Area estimation of land cover change and drivers
The area estiamtes for land cover change for 2023 are derived from a probability sample of reference data. The sample was stratified by land cover type as well as by change detection within DIST-ALERT. The selected sample of 30 m pixels were labeled through a time-series of 2023 with resulting reference data contained in referenceTimeSeries.csv and referenceTimeSeriesInterpolated16.csv. The driver, conversion label, and possible natural vegetation loss are recorded in reference_conversion.csv. The functions and calculations for estimating the area of various drivers of change is in area.ipynb along with figures.

## DIST-ALERT performance assessment
The probability sample of time-series reference data enabled us to quantify the accuracy of DIST-ALERT applicable to any date with updated map data in 2023. Additionally metrics of latency and timeliness are quantified. These estimations and figures are included in DISTperformance.ipynb. To view the latest DIST-ALERT composite and access on Google Earth Engine see: https://glad.earthengine.app/view/dist-alert. Additional documentation and the full time-series is available from NASA which is the authoritative data source: https://doi.org/10.5067/SNWG/OPERA_L3_DIST-ALERT-HLS_V1.001. DIST-ALERT is produced as part of the OPERA project, which is funded by NASA to address remote sensing needs identified by the Satellite Needs Working Group. Managed by NASA’s Jet Propulsion Laboratory, OPERA funds and manages UMD GLAD’s DIST-ALERT product development.

## Citation
All codes included here were used for estimating the statistics in a submitted manuscript:

A.H. Pickens, M.C. Hansen, Z. Song, A. Poulson, A. Komarova, A. Baggett, T. Kerr, A. Mikus, C. Ortiz Dominguez, A. Tyukavina, A. Lima. Global land change monitoring in near-real time. _Submitted_

### Questions?
Reach out to ahudson2 _at_ umd.edu.
