fips-entt
=========

fipsified entt (https://github.com/skypjack/entt)

fips build system: https://github.com/floooh/fips

## How to integrate:

Add the dependency to your fips.yml file:

```yaml
imports:
    fips-entt:
        git: https://github.com/melMass/fips-entt
```

```cmake
set(CMAKE_CXX_STANDARD 17) # required for entt
fips_begin_*(...)
    ...
    fips_deps(entt)
fips_end_*(...)
```
