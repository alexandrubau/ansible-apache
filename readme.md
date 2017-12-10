## Apache role

Some description for Apache role would be nice. Any volunteers?

### Parameters

**apache_version** (type `string`, default `2.4.*`)

Example:
```yaml
apache_version: 2.4.*
```

**apache_configs** (type `object`, defalt `{}`)

Example:
```yaml
apache_configs:
  fqdn: /vagrant/templates/fqdn.conf.j2
```

**apache_mods** (type `array`, default `[]`)

Example:
```yaml
apache_mods:
  - rewrite
  - headers
```

**apache_sites** (type `object`, default `{}`)

Example:
```yaml
apache_sites:
  athena: /vagrant/templates/athena.conf.j2
```