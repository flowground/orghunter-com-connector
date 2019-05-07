# ![LOGO](logo.png) OrgHunter **flow**ground Connector

## Description

A generated **flow**ground connector for the OrgHunter API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/orghunter.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:29+03:00

## API Description

Get the latest IRS data and most up to date charity information for your website or application

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Get categories!

> <p>This operation provides a list of categories.</p>

*Tags:* `categories`

### Get details!

> <p>This operation detail data.</p>

*Tags:* `details`

#### Input Parameters
* `ein` - _optional_ - ein (Employer Identification Number)

### Get details!

> <p>This operation detail data.</p>

*Tags:* `CharityFinancial`

#### Input Parameters
* `ein` - _optional_ - ein (Employer Identification Number)

### Get details!

> <p>This operation detail data.</p>

*Tags:* `GeoLocation`

#### Input Parameters
* `ein` - _optional_ - ein (Employer Identification Number)

### Get details!

> <p>This operation detail data.</p>

*Tags:* `CharityPremium`

#### Input Parameters
* `ein` - _optional_ - ein (Employer Identification Number)

### Get summary data!

> <p>This operation provides summary data.</p>

*Tags:* `summary`

#### Input Parameters
* `ein` - _optional_ - Employer Identification Number (EIN)
* `searchTerm` - _optional_ - Charity Name or Keyword. Example: humane society or cancer
* `city` - _optional_ - City Name. Example: Miami
* `state` - _optional_ - State Name - Two letter state abbreviation
* `zipCode` - _optional_ - Zipcode Value - 5 digit zipcode value
* `category` - _optional_ - Category Value Selected from Categories API
* `eligible` - _optional_ - eligible=1 will return only organizations that are tax deductible and in good standing with the IRS
* `start` - _optional_ - Record Set Start Position
* `rows` - _optional_ - Records Per Page. Default Value = 20

## License

**flow**ground :- Telekom iPaaS / orghunter-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
