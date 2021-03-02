
# API Current Release <small>([View All](/API.md))</small>
## 5.19.3 (2021-2-24)
### Patches 

> fixed the json post to phonism where the options are being sent down as a json array of options to phonism client

```php
$res = $this->client->request($method, self::$URL . $url, ['json' => $options]);
```



<br><br>
# Web Current Release <small>([View All](/Web.md))</small>
## 5.19.4 (2021-3-2)
### Patches 

- Breadcrumb issue fixes #783
- Change path name
- Group Call Park Breadcrumb fixed to insert correct serviceProviderId and groupId

  