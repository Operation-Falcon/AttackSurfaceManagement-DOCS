
## Attack Surface Management **Config**

!!! abstract "config"

    Since AttackSurfaceManagement uses various security engine and platforms too, it is neccessary to upload the configuration
    file locate at `$HOME/configuration/config.yaml` for maximum coverage . It uses platform such as :

    1. [Shodan]()
    2. [Binary Edge]()
    3. [Censys]()
    4. [TomTomapi]()
    5. [IntelX]()
    6. [Security Trails]()
    7. [Spyse]()
    8. [Risk IQ]()
    9. [Virus Total]()
    10. [Hunter.io]()

Here is an example config file:-

```yaml
# EXample of config.yaml file.
API:
  - Binary_edge: api_key
  - Shodan: api_key
  - Censys: api_key
  - TomTomapi: api_key
  - IntelX: api_key
  - Security_trails: api_key
  - Spyse: api_key
  - Risk_iq: api_key
  - Virus_total: api_key
  - Hunter.io: api_key
  - Threat_exchange: api_key


```

**Config file be used as default**.
