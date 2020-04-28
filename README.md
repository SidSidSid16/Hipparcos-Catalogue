# Hipparcos-Catalogue

## The Hipparcos Main Catalogue
This repository contains the Hipparcos Main Astrometric Catalogue in various file formats.

### Details
- Catalogue Pulled From [VizieR (Mirror: CDS, France)](http://vizier.u-strasbg.fr/)
- Author: ESA
- Year: 1997
- 118218 stars

#### Available File Formats
- Tab Separated Values (.tsv)
- Comma Separated Values (.csv)
- Strict Open XML Spreadsheet (.xlsx)
- Excel 97-2004 Workbook (.xls)
- Web Page (.htm)

#### Table Columns
| Column | Data type | Details |
| --- | --- | --- |
| HIP | string | Catalogue identifier number |
| RAhms | string (hours minutes seconds) | Right ascension in h m s, ICRS (J1991.25) |
| DEdms | string (degrees minutes seconds) | Right ascension in h m s, ICRS (J1991.25)|
| Vmag | (magnitude) | Magnitude in Johnson V |
| RAICRS | (degrees) | alpha, degrees (ICRS, Epoch=J1991.25) |
| DEICRS | (degrees) | delta, degrees (ICRS, Epoch=J1991.25) |
| Plx | (milli-seconds of arc) | Trigonometric parallax |
| pmRA | (milli-seconds of arc per year) | Proper motion mu_alpha.cos(delta), ICRS(H12) (for J1991.25 epoch) |
| pmDE | (milli-seconds of arc per year) | Proper motion mu_delta, ICRS (H13) (for J1991.25 epoch) |
| e_Plx | (milli-seconds of arc) | Standard error in Plx |
| B-V | (magnitude) | Johnson B-V colour |
| Notes | char |  |
| \_RA.icrs | (degrees) | Right Ascension (ICRS, epoch 2000) |
| \_DE.icrs | (degrees) | Declination (ICRS, epoch 2000) |

### Usage
This dataset is intended to be used with the StarMapLite project but can also be used for any other projects. This catalogue has been converted into multiple file formats for ease of use when porting into your project.
