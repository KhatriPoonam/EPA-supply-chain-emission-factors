<!-- README.md is generated from README.Rmd. Please edit that file -->

# Supply Chain GHG Emission Factors

Code and reproductions of the [Supply Chain GHG Emission
Factors](https://cfpub.epa.gov/si/si_public_record_Report.cfm?dirEntryId=349324).

## Model Descriptions

| Model Name           | \# of Sectors | Commodity (C) or Industry (I) | IO Data Year | GHG and Economic Output Year |
|:---------------------|--------------:|------------------------------:|-------------:|-----------------------------:|
| USEEIOv2.0.10-GHG    |           405 |                     Commodity |         2012 |                         2010 |
| USEEIOv2.0.10-i-GHG  |           405 |                      Industry |         2012 |                         2010 |
| USEEIOv2.0.10-is-GHG |            71 |                      Industry |         2012 |                         2010 |
| USEEIOv2.0.10-s-GHG  |            73 |                     Commodity |         2012 |                         2010 |
| USEEIOv2.0.11-GHG    |           405 |                     Commodity |         2012 |                         2011 |
| USEEIOv2.0.11-i-GHG  |           405 |                      Industry |         2012 |                         2011 |
| USEEIOv2.0.11-is-GHG |            71 |                      Industry |         2012 |                         2011 |
| USEEIOv2.0.11-s-GHG  |            73 |                     Commodity |         2012 |                         2011 |
| USEEIOv2.0.12-GHG    |           405 |                     Commodity |         2012 |                         2012 |
| USEEIOv2.0.12-i-GHG  |           405 |                      Industry |         2012 |                         2012 |
| USEEIOv2.0.12-is-GHG |            71 |                      Industry |         2012 |                         2012 |
| USEEIOv2.0.12-s-GHG  |            73 |                     Commodity |         2012 |                         2012 |
| USEEIOv2.0.13-GHG    |           405 |                     Commodity |         2012 |                         2013 |
| USEEIOv2.0.13-i-GHG  |           405 |                      Industry |         2012 |                         2013 |
| USEEIOv2.0.13-is-GHG |            71 |                      Industry |         2012 |                         2013 |
| USEEIOv2.0.13-s-GHG  |            73 |                     Commodity |         2012 |                         2013 |
| USEEIOv2.0.14-GHG    |           405 |                     Commodity |         2012 |                         2014 |
| USEEIOv2.0.14-i-GHG  |           405 |                      Industry |         2012 |                         2014 |
| USEEIOv2.0.14-is-GHG |            71 |                      Industry |         2012 |                         2014 |
| USEEIOv2.0.14-s-GHG  |            73 |                     Commodity |         2012 |                         2014 |
| USEEIOv2.0.15-GHG    |           405 |                     Commodity |         2012 |                         2015 |
| USEEIOv2.0.15-i-GHG  |           405 |                      Industry |         2012 |                         2015 |
| USEEIOv2.0.15-is-GHG |            71 |                      Industry |         2012 |                         2015 |
| USEEIOv2.0.15-s-GHG  |            73 |                     Commodity |         2012 |                         2015 |
| USEEIOv2.0.16-GHG    |           405 |                     Commodity |         2012 |                         2016 |
| USEEIOv2.0.16-i-GHG  |           405 |                      Industry |         2012 |                         2016 |
| USEEIOv2.0.16-is-GHG |            71 |                      Industry |         2012 |                         2016 |
| USEEIOv2.0.16-s-GHG  |            73 |                     Commodity |         2012 |                         2016 |

## Usage

``` r
install.packages("rmarkdown")
rmarkdown::render("CalculateEmissionFactors.Rmd", params = "ask")
```

# Disclaimer

The United States Environmental Protection Agency (EPA) GitHub project
code is provided on an “as is” basis and the user assumes responsibility
for its use. EPA has relinquished control of the information and no
longer has responsibility to protect the integrity , confidentiality, or
availability of the information. Any reference to specific commercial
products, processes, or services by service mark, trademark,
manufacturer, or otherwise, does not constitute or imply their
endorsement, recommendation or favoring by EPA. The EPA seal and logo
shall not be used in any manner to imply endorsement of any commercial
product or activity by EPA or the United States Government.
