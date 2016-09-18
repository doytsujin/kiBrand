# kibana-logo-hack
Kibana Plugin for Logo Neutralization

<img src="http://i.imgur.com/61132PJ.png" />

### Installation
```
bin/kibana plugin --install kibana-logo-hack -u https://github.com/elasticfence/kibana-logo-hack/archive/master.tar.gz
```

#### Configuration
Add your custom branding preferences to ```config/kibana.yml``` 
```
kibana-logo-hack.enabled: true
kibana-logo-hack.name: "NULL"
# kibana-logo-hack.logourl: "http://127.0.0.2/some/logo.svg"

```
#### Runtime Usage
* Custom Brand
```
BRAND="NULL" bin/kibana
```

* Custom Logo (local)
```
LOGOURL="/bundles/src/ui/public/images/kibana.svg" bin/kibana
```
* Custom Logo (remote)
```
LOGOURL="http://127.0.0.2/some/logo.svg" bin/kibana
```



#### Todo:
* Add custom logo and css management
