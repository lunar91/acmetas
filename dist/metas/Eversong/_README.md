# Everson Metas

## Requirements
Unless otherwise specified, all of the Everson metas have these requirements:
- Plugins
  - Utility Belt
  - Mag-Tools
  - Virindi Tank
- Configuration
  - Override Virindi Tank meta expressions with Utility Belt meta expressions (Automatically set by the metas on start in the Default state)
- You must have Town Network Recall Gems for each difficulty.

# Configuration Eversong Metas
This collection of Eversong Metas includes configuration for setting the order to run difficulties in AND configuring a minimum and maximum difficulty.

**Realms**: `Normal,Hard,Expert,Master,Nightmare,Torment,Torment II,Torment III,Torment IV,Torment V,Torment VI`
- Minimum Realm: `/ub mexec @minRealm=REALM` replace REALM with any realm. Case-sensitive.
- Maximum Realm: `/ub mexec @maxRealm=REALM` replace REALM with any realm. Case-sensitive.
- Order of Completion: `/ub mexec @realmOrder=DOWN` use `DOWN` to go from highest to lowest difficulty. Any other value goes from lowest to highest difficulty. Case-sensitive.



