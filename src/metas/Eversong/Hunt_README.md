# Hunting Meta

This meta is a generic hunting meta AND requires some setup. Persistent Utility Belt variables will hold your Nav and Realm information. This makes it so this single meta can be used for many different hunting locations independent of realm.

## Setup
- You must set the following variables by using `/ub mexec @varName=``value`` `
  - **@huntRealm** The Realm to hunt in.
    - One of `Normal,Hard,Expert,Master,Nightmare,Torment,Torment II,Torment III,Torment IV,Torment V,Torment VI`
  - **@huntNav** The Nav Name of your hunting nav.
  - **@returnNav** The Nav Name of a nav to RETURN to your hunting nav start.
  - **@navStartInRealm** (optional, default=0) When set to any value other than `0`, the meta will start the return by using a TN gem of the corresponding realm.]
  

### Example
In the below example, I'm hunting TouTou in `Torment VI`. My hunting nav is `TouTou.nav` and my return nav is `TouTou_Return.nav`. The Return nav starts from the Town Network drop because `@navStartInRealm=1` causes the meta to start at TN in the `@huntRealm`

```
  /ub mexec @huntRealm=`Torment VI`
  /ub mexec @huntNav=`TouTou`
  /ub mexec @returnNav=`TouTou_Return`
  /ub mexec @navStartInRealm=1
```

