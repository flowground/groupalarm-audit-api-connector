# ![LOGO](logo.png) groupalarm Audit API **flow**ground Connector

## Description

A generated **flow**ground connector for the groupalarm Audit API API (version 1.15.0).

Generated from: https://app.groupalarm.com/api/v1/audit<br/>
Generated at: 2019-07-26T13:59:33+03:00

## API Description

The audit service implements the an organization log service, to observe all actions inside an organization<br/>
<br/>
# Authentication<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>

## Authorization

Supported authorization schemes:
- API Key
- API Key

## Actions

### ListEvents
> List all logged organization actions for passed organization id<br/>

*Tags:* `events`

#### Input Parameters
* `organization_id` - _optional_
* `limit` - _optional_ - limits audit list output to passed amount.<br/>
* `offset` - _optional_ - defines the offset for pagination<br/>

## License

**flow**ground :- Telekom iPaaS / groupalarm-audit-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
