# Hipparcos-Catalogue

## The Hipparcos Main Catalogue
This repository contains the Hipparcos Main Astrometric Catalogue in a Comma Separated Values file (.csv) and an Microsoft Excel file (.xlsx) 

#### Details
- Catalogue Pulled From [VizieR](http://vizier.u-strasbg.fr/)
- Author: ESA
- Year: 1997
- 118218 stars

#### Table Columns
| Column | Data type | Details |
| --- | --- | --- |
| HIP | string | Catalogue identifier number |
| Vmag | (magnitude) | Magnitude in Johnson V |
| Plx | (milli-seconds of arc) | Trigonometric parallax |
| pmRA | (milli-seconds of arc per year) | Proper motion mu_alpha.cos(delta), ICRS(H12) (for J1991.25 epoch) |
| pmDE | (milli-seconds of arc per year) | Proper motion mu_delta, ICRS (H13) (for J1991.25 epoch) |
| e_Plx | (milli-seconds of arc) | Standard error in Plx |
| B-V | (magnitude) | Johnson B-V colour |
| Notes | char |  |
| \_RA.icrs | (degrees) | Right Ascension (ICRS, epoch 2000) |
| \_DE.icrs | (degrees) | Declination (ICRS, epoch 2000) |

#### Usage
This dataset is intended to be used with the StarMapLite project but can be used for other purposes quite easily as it is in a .csv file. A .xlsx file is also included for easy use with Microsoft Excel.
