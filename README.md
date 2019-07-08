# ![LOGO](logo.png) OrgHunter **flow**ground Connector

## Description

A generated **flow**ground connector for the OrgHunter API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/orghunter.com/1.0.0/swagger.json<br/>
Generated at: 2019-07-08T14:35:57+03:00

## API Description

Get the latest IRS data and most up to date charity information for your website or application<br/>

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Get categories!
<blockquote><p>This operation provides a list of categories.</p></blockquote>

*Tags:* `categories`

### Get details!
<blockquote><p>This operation detail data.</p></blockquote>

*Tags:* `details`

#### Input Parameters
* `ein` - _optional_ - ein (Employer Identification Number)<br/>

### Get details!
<blockquote><p>This operation detail data.</p></blockquote>

*Tags:* `CharityFinancial`

#### Input Parameters
* `ein` - _optional_ - ein (Employer Identification Number)<br/>

### Get details!
<blockquote><p>This operation detail data.</p></blockquote>

*Tags:* `GeoLocation`

#### Input Parameters
* `ein` - _optional_ - ein (Employer Identification Number)<br/>

### Get details!
<blockquote><p>This operation detail data.</p></blockquote>

*Tags:* `CharityPremium`

#### Input Parameters
* `ein` - _optional_ - ein (Employer Identification Number)<br/>

### Get summary data!
<blockquote><p>This operation provides summary data.</p></blockquote>

*Tags:* `summary`

#### Input Parameters
* `ein` - _optional_ - Employer Identification Number (EIN)<br/>
* `searchTerm` - _optional_ - Charity Name or Keyword. Example: humane society or cancer<br/>
* `city` - _optional_ - City Name. Example: Miami<br/>
* `state` - _optional_ - State Name - Two letter state abbreviation<br/>
* `zipCode` - _optional_ - Zipcode Value - 5 digit zipcode value<br/>
* `category` - _optional_ - Category Value Selected from Categories API<br/>
* `eligible` - _optional_ - eligible=1 will return only organizations that are tax deductible and in good standing with the IRS<br/>
* `start` - _optional_ - Record Set Start Position<br/>
* `rows` - _optional_ - Records Per Page. Default Value = 20<br/>

## License

**flow**ground :- Telekom iPaaS / orghunter-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
