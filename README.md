# Repo with applications settings

### Usage
Settings are loaded into apps by Spring Cloud Config Server.
All settings are stored in the yaml format.

### Repo structure
* `application.yml` - common settings for all apps and all stages
* `application-integration.yml` - settings for **integration** environment. For **spring.profiles.active=integration**
* `application-production.yml` - settings for **production** environment. For **spring.profiles.active=production**
* `encryptor.yml` - settings for **encryptor** (independent from stage)
