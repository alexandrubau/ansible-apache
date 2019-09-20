## Apache role

Some description for Apache role would be nice. Any volunteers?

### Parameters

**apache_version** (type `string`, default `2.4.*`)

Example:
```yaml
apache_version: 2.4.*
```

**apache_modules** (type `array`, default `[]`)

Example:
```yaml
apache_modules:
  - rewrite
  - headers
```

**apache_configs** (type `object`, defalt `[]`)

Example:
```yaml
apache_configs:
  - name: fqdn
    path: /vagrant/templates/fqdn.conf.j2
```

**apache_sites** (type `object`, default `[]`)

Example:
```yaml
apache_sites:
  - name: athena
    path: /vagrant/templates/athena.conf.j2
```