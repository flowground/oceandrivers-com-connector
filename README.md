# ![LOGO](logo.png) ODWeather **flow**ground Connector

## Description

A generated **flow**ground connector for the ODWeather API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/oceandrivers.com/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:23+03:00

## API Description

This is the api to access the ODWeather API information

## Authorization

This API does not require authorization.

## Actions

### Get forecast and realtime information for known points<br/>None

*Tags:* `ODWeather`

#### Input Parameters
* `stationName` - _required_ - Weather station to compare, values: cnareanl|rcnp | cmsap|boyaenderrocat|areopuertopalma

### Get data from the aemet stations<br/>None

*Tags:* `ODWeather`

#### Input Parameters
* `stationName` - _required_ - station name currently: aeropuertopalma | caboblanco 
* `period` - _required_ - Period of time to get the data. Options: lastdata lastday

### Get data from the easywind weather stations<br/>None

*Tags:* `ODWeather`

#### Input Parameters
* `easywindId` - _required_ - currently: 'EW013'|'EW008'|'EW006'|'EW007'
* `period` - _required_ - Period of time to get the data latestdata|latesthour|latestday

### Get stations in an event<br/>None

*Tags:* `ODWeather`

#### Input Parameters
* `eventId` - _required_ - currently: 'trofeoprincesasofia'

### Get forecast points of a yatchclub<br/>None

*Tags:* `ODWeather`

#### Input Parameters
* `yatchclubid` - _required_ - base URL for the the
* `language` - _required_

### Get timeseries forecast information<br/>None

*Tags:* `ODWeather`

#### Input Parameters
* `latitude` - _required_ - latitude for the forecast
* `longitude` - _required_ - longitude for the forecast
* `inittime` - _optional_ - initial date for the forecast ISO string YYYY-MM-DDTHH:mm:SS.SZ
* `endtime` - _optional_ - end date for the forecast ISO string YYYY-MM-DDTHH:mm:SS.SZ
* `days` - _optional_ - optional number of days in string. Will be added to init forecast date
* `hours` - _optional_ - optional number of hours in string. Will be added to init forecast date
* `weather` - _required_ -  Comma separated values for the weather parameteres temperature,rain,wind_u,wind_v,gust,pressure,cloud,humidity&wave=height,direction,period
* `wave` - _optional_ -  Comma separated values for the wave parameteres height,direction,period
* `entryid` - _optional_ - Direct file I want to extract

### Get timeseries forecast information<br/>None

*Tags:* `ODWeather`

#### Input Parameters
* `latitude` - _required_ - latitude for the forecast
* `longitude` - _required_ - longitude for the forecast
* `inittime` - _optional_ - initial date for the forecast ISO string YYYY-MM-DDTHH:mm:SS.SZ
* `endtime` - _optional_ - end date for the forecast ISO string YYYY-MM-DDTHH:mm:SS.SZ
* `days` - _optional_ - optional number of days in string. Will be added to init forecast date
* `hours` - _optional_ - optional number of hours in string. Will be added to init forecast date
* `weather` - _required_ -  Comma separated values for the weather parameteres temperature,rain,wind_u,wind_v,gust,pressure,cloud,humidity&wave=height,direction,period
* `wave` - _optional_ -  Comma separated values for the wave parameteres height,direction,period
* `entryid` - _optional_ - Direct file I want to extract

### Get data from the socib bahia de palma buoy<br/>None

*Tags:* `ODWeather`

#### Input Parameters
* `stationName` - _required_ - station name currently: boyaenderrocat | playadepalma
* `period` - _required_ - Period of time to get the data. Options: lastdata lasthour lastday

### Get data from the weather display software<br/>None

*Tags:* `ODWeather`

#### Input Parameters
* `stationName` - _required_ - currently: 'cnarenal'|'campastilla' | 'cncg'
* `period` - _required_ - Period of time to get the data latestdata|latesthour|latestday|dailylog

### Get forecast and realtime information for known points<br/>None

*Tags:* `ODWeather`

## License

**flow**ground :- Telekom iPaaS / oceandrivers-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
