
# API Current Release <small>([View All](/API.md))</small>
## 5.19.2 (2021-2-24)
# odin-api release notes

## Mac Address Fix (2021-02-24) (5.19.2) 

>fixed the response of *macAddress* integer to string for macAddresses with only numbers.
>
>This impacted all levels of devices **System**, **ServiceProvider** and **Group**  *devices*.
>
>Example: *macAddress*: **556688995566** is now *macAddress*: **"556688995566"**

Before

```json
{
    "serviceProviderId": "ent.odin",
    "groupId": "grp.odin",
    "deviceName": "1000_1_grp.odin",
    "deviceType": "Polycom VVX 500 DM",
    "protocol": "SIP 2.0",
    "macAddress": 556688995566,
}
```

After
```json
{
    "serviceProviderId": "ent.odin",
    "groupId": "grp.odin",
    "deviceName": "1000_1_grp.odin",
    "deviceType": "Polycom VVX 500 DM",
    "protocol": "SIP 2.0",
    "macAddress": "556688995566",
}

```

<br><br>
# Web Current Release <small>([View All](/Web.md))</small>
## 5.19.1 (2021-2-23)
sync with api

  