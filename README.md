# ![LOGO](logo.png) CBB v3 Scores **flow**ground Connector

## Description

A generated **flow**ground connector for the CBB v3 Scores API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/cbb-v3-scores/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:29+03:00

## API Description



## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### Are Games In Progress

> Returns <code>true</code> if there is at least one game being played at the time of the request or <code>false</code> if there are none.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Current Season

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Schedules

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season (with optional season type).<br>Examples: <code>2018</code>, <code>2018PRE</code>, <code>2018POST</code>, <code>2018STAR</code>, <code>2019</code>, etc.

### Games by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2018-FEB-27</code>, <code>2017-DEC-01</code>.

### League Hierarchy

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Player Details by Player

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `playerid` - _required_ - Unique FantasyData Player ID.
Example:<code>60003802</code>.

### Player Details by Active

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Player Details by Team

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `team` - _required_ - The abbreviation of the requested team.
<br>Examples: <code>SF</code>, <code>NYY</code>.

### Stadiums

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Team Game Stats by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the game(s).
<br>Examples: <code>2018-FEB-27</code>, <code>2017-DEC-01</code>.

### Team Season Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season (with optional season type).<br>Examples: <code>2018</code>, <code>2018POST</code>, <code>2019</code>.

### Tournament Hierarchy

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season (with optional season type).<br>Examples: <code>2018</code>, <code>2018POST</code>, <code>2019</code>.

### Teams

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-cbb-v-3-scores-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
