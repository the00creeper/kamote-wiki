# spigot.yml

{% hint style="warning" %}
Any setting shown as `[CLASSIFIED]` has been hidden for **server security reasons**.
{% endhint %}

{% code title="spigot.yml" fullWidth="false" %}
```yml
players:
  disable-saving: false
world-settings:
  default:
    below-zero-generation-in-existing-chunks: true
    entity-activation-range:
      animals: 16
      monsters: 24
      raiders: 48
      misc: 8
      water: 8
      villagers: 16
      flying-monsters: 48
      wake-up-inactive:
        animals-max-per-tick: 4
        animals-every: 1200
        animals-for: 100
        monsters-max-per-tick: 8
        monsters-every: 400
        monsters-for: 100
        villagers-max-per-tick: 4
        villagers-every: 600
        villagers-for: 100
        flying-monsters-max-per-tick: 8
        flying-monsters-every: 200
        flying-monsters-for: 100
      villagers-work-immunity-after: 100
      villagers-work-immunity-for: 20
      villagers-active-for-panic: true
      tick-inactive-villagers: false
      ignore-spectators: false
    nerf-spawner-mobs: false
    enable-zombie-pigmen-portal-spawns: true
    view-distance: default
    end-portal-sound-radius: 0
    arrow-despawn-rate: 1200
    trident-despawn-rate: 1200
    zombie-aggressive-towards-villager: true
    merge-radius:
      item: 4
      exp: 6
    item-despawn-rate: 6000
    hanging-tick-frequency: 100
    wither-spawn-sound-radius: 0
    simulation-distance: default
    thunder-chance: 100000
    unload-frozen-chunks: false
    mob-spawn-range: 3
    growth:
      cactus-modifier: 100
      cane-modifier: 100
      melon-modifier: 100
      mushroom-modifier: 100
      pumpkin-modifier: 100
      sapling-modifier: 100
      beetroot-modifier: 100
      carrot-modifier: 100
      potato-modifier: 100
      torchflower-modifier: 100
      wheat-modifier: 100
      netherwart-modifier: 100
      vine-modifier: 100
      cocoa-modifier: 100
      bamboo-modifier: 100
      sweetberry-modifier: 100
      kelp-modifier: 100
      twistingvines-modifier: 100
      weepingvines-modifier: 100
      cavevines-modifier: 100
      glowberry-modifier: 100
      pitcherplant-modifier: 100
    entity-tracking-range:
      players: 96
      animals: 48
      monsters: 96
      misc: 32
      display: 64
      other: 64
    ticks-per:
      hopper-transfer: 8
      hopper-check: 1
    hopper-amount: 1
    hopper-can-load-chunks: false
    dragon-death-sound-radius: 0
    seed-village: [CLASSIFIED]
    seed-desert: [CLASSIFIED]
    seed-igloo: [CLASSIFIED]
    seed-jungle: [CLASSIFIED]
    seed-swamp: [CLASSIFIED]
    seed-monument: [CLASSIFIED]
    seed-shipwreck: [CLASSIFIED]
    seed-ocean: [CLASSIFIED]
    seed-outpost: [CLASSIFIED]
    seed-endcity: [CLASSIFIED]
    seed-slime: [CLASSIFIED]
    seed-nether: [CLASSIFIED]
    seed-mansion: [CLASSIFIED]
    seed-fossil: [CLASSIFIED]
    seed-portal: [CLASSIFIED]
    seed-ancientcity: [CLASSIFIED]
    seed-trailruins: [CLASSIFIED]
    seed-trialchambers: [CLASSIFIED]
    seed-buriedtreasure: [CLASSIFIED]
    seed-mineshaft: [CLASSIFIED]
    seed-stronghold: [CLASSIFIED]
    hunger:
      jump-walk-exhaustion: 0.05
      jump-sprint-exhaustion: 0.2
      combat-exhaustion: 0.1
      regen-exhaustion: 6.0
      swim-multiplier: 0.01
      sprint-multiplier: 0.1
      other-multiplier: 0.0
    max-tnt-per-tick: 100
    max-tick-time:
      tile: 50
      entity: 50
    verbose: false
  worldeditregentempworld:
    verbose: false
messages:
  whitelist: You are not whitelisted on this server!
  unknown-command: Unknown command. Type "/help" for help.
  server-full: The server is full!
  outdated-client: Outdated client! Please use {0}
  outdated-server: Outdated server! I'm still on {0}
  restart: Server is restarting
settings:
  timeout-time: 360
  restart-on-crash: true
  restart-script: [CLASSIFIED]
  netty-threads: [CLASSIFIED]
  attribute:
    maxAbsorption:
      max: 2048.0
    maxHealth:
      max: 1024.0
    movementSpeed:
      max: 1024.0
    attackDamage:
      max: 2048.0
  log-villager-deaths: true
  log-named-deaths: true
  save-user-cache-on-stop-only: false
  user-cache-size: 1000
  bungeecord: false
  moved-too-quickly-multiplier: 5.0
  moved-wrongly-threshold: 0.5
  player-shuffle: 0
  sample-count: 12
  debug: false
advancements:
  disable-saving: false
  disabled:
  - minecraft:story/disabled
config-version: 12
stats:
  disable-saving: false
  forced-stats: {}
commands:
  log: true
  replace-commands:
  - setblock
  - summon
  - testforblock
  - tellraw
  tab-complete: 0
  send-namespaced: true
  spam-exclusions:
  - /skill
  silent-commandblock-console: false
  enable-spam-exclusions: false

```
{% endcode %}
