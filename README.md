# Analysis of Facebook Pixels and Politicians' Campaign Websites - WIRED

This repository includes data supporting the following article, published by WIRED:
- "TITLE TK" (June 26, 2019) — [WIRED](LINK TK)

## Data Overview
From **June 11-22, 2019**, Wired analyzed the presence of Facebook pixels on the publicly available campaign websites of 535 US politicians using the publicly available Facebook Pixel Helper Chrome extension. We also made the minimum possible donation (usually $1) to 110 US politicians and analyzed the presence of Facebook pixels on each of the donation confirmation pages. Data from our analyses are available in the following three CSVs:
- **us_senators_pixels.csv** contains data about the presence of Facebook pixels on the landing pages and donation confirmation pages of 99 sitting US senators to whom we were able to donate
- **us_house_pixels.csv** contains data about the presence of Facebook pixels on the landing pages of 425 sitting members of the US House of Representatives whose campaign websites we were able to find
- **us_presidential_candidates_pixels.csv** contains data about the presence of Facebook pixels on the landing pages and donation confirmation pages of 21 presidential candidates for the 2020 campaign

For US senators and presidential candidates, this repository also includes screenshots of the output from Facebook Pixel Helper on each of the relevant landing pages and donation confirmation pages.

## Data Dictionary
- **us_senators_pixels.csv**
  - NAME: Name
  - STATE: State
  - SABB: State Abbreviation
  - P: Party
  - LEY: Last Election Year
  - CLASS: Class (from https://www.senate.gov/general/contact_information/senators_cfm.cfm)
  - COMMITTEES: Committees (from https://www.senate.gov/general/committee_assignments/assignments.htm)
  - WEBSITE: Official Campaign Website
  - LPP: Landing Page Pixel, 1 = YES, 0 = NO **(AS OF JUNE 22, 2019)**
  - DPP: Donation Confirmation Page Pixel, AMT = Pixel passing back exact donation amount, STD = Standard Pixel, 0 = No Pixel **(AS OF JUNE 11-14, 2019)**
  - VENDOR: Vendor listed on Donation Confirmation Page **(AS OF JUNE 11-14, 2019)**
  - FBP: Facebook Pixel on either Landing Page OR Donation Confirmation Page **(AS OF JUNE 11-22, 2019)**

- **us_house_pixels.csv**
  - NAME: Name
  - STATE: State
  - SABB: State Abbreviation
  - DISTRICT: District
  - PARTY: Party
  - COMMITTEES: Committees (from https://www.house.gov/representatives)
  - WEBSITE: Official Campaign Website
  - LPP: Landing Page Pixel, 1 = YES, 0 = NO **(AS OF JUNE 10, 2019)**

- **us_presidential_candidates_pixels.csv**
  - NAME: Name
  - P: Party
  - WEBSITE: Official Campaign Website
  - LPP: Landing Page Pixel, 1 = YES, 0 = NO **(AS OF JUNE 22, 2019)**
  - DPP: Donation Confirmation Page Pixel, AMT = Pixel passing back exact donation amount, STD = Standard Pixel, 0 = No Pixel **(AS OF JUNE 11-14, 2019)**
  - VENDOR	Vendor listed on Donation Confirmation Page **(AS OF JUNE 11-14, 2019)**
  - FBP	Facebook Pixel on either Landing Page OR Donation Confirmation Page **(AS OF JUNE 11-22, 2019)**
  
## Data Disclaimer
We are sharing our data in order to support further research and reporting on web tracking technologies. We have carefully checked the accuracy of our data and analysis as of the dates listed above. However, users of this data are advised that the code on any given website is subject to being modified at any time.  Users of this data may wish to independently verify the accuracy of their findings prior to making them public, as Wired makes no representations or warranties as to any third party use of this data.

## Licensing
All data files in this repository are available under the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0) license.

## Questions / Comments?
Please contact Hamdan Azhar at hamdan dot azhar at gmail dot com.
