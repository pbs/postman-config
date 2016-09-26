# postman-config
Postman configurations for PBS APIs

# Usage
Herein are PBS-specific configuration files for the Postman application. (www.getpostman.com)

The configuration files fall under two categories: (1) collections and (2) environments. 

Collections are aggregates of URLs with a common or similar purpose. Environments are runtime enviroments that document which parameters should be used when making requests via a particular Collections. 

Ideally, for ease of use, the name of a Collection matches the name of its usable Environment. 

# API-specific notes

### COVE API

#### Collections: 

BasicAuth (internal use) - example of Basic Auth for internal use
MvaultWindowing - example of filtering Mvault content
DigestAuth - example of Digest Auth-ish URL signing

#### Environemnts

BasicAuth-Template - defined params for basic auth user/pass
DigestAuth-Template  - defined params for digest auth key/secret
