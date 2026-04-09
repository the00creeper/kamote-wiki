# bukkit.yml

{% hint style="warning" %}
Any setting shown as `[CLASSIFIED]` has been hidden for **server security reasons**.
{% endhint %}

{% code title="bukkit.yml" fullWidth="false" %}
```yml
settings:
  allow-end: true
  warn-on-overload: true
  permissions-file: permissions.yml
  update-folder: update
  plugin-profiling: false
  connection-throttle: [CLASSIFIED]
  query-plugins: [CLASSIFIED]
  deprecated-verbose: default
  shutdown-message: Server closed
  minimum-api: none
  use-map-color-cache: true
spawn-limits:
  monsters: 20
  animals: 5
  water-animals: 2
  water-ambient: 2
  water-underground-creature: 3
  axolotls: 5
  ambient: 1
chunk-gc:
  period-in-ticks: 400
ticks-per:
  animal-spawns: 300
  monster-spawns: 10
  water-spawns: 400
  water-ambient-spawns: 400
  water-underground-creature-spawns: 400
  axolotl-spawns: 400
  ambient-spawns: 400
  autosave: 6000
aliases: now-in-commands.yml

```
{% endcode %}
