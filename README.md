# Flying Tank Glitch Sandbox

A Three.js browser game featuring a tank with bunnyhopping mechanics and flying glitch zones.

<img width="2554" height="1180" alt="image" src="https://github.com/user-attachments/assets/bcfef900-866c-460d-af6c-880714512788" />

## Play

Open `index.html` in a browser.

## Controls

- **WASD** - Move tank
- **SPACE** - Jump (hold for auto-bhop)
- **R** - Reset position

## Features

- **Bunnyhopping** - Hold spacebar while moving to chain jumps and gain exponential speed
- **Air Control** - Turn and strafe while airborne
- **Glitch Zones** - Drive into red zones to trigger the flying glitch and get launched
- **Infinite World** - Procedurally generated terrain with trees, rocks, and glitch zones
- **No Speed Cap** - Chain enough bhops and go as fast as you want

## Mechanics

The bunnyhopping system uses exponential speed growth. Each successful bhop multiplies your speed by 1.15x plus a base boost. The longer your chain, the faster you accelerate.

## Inspiration

This game combines mechanics from two classic game glitches:

### Flying Tank Glitch (World of Tanks)
A physics bug where tanks could be launched hundreds of meters into the air. Driving over destroyed tank turrets or hitting certain terrain geometry would cause the physics engine to "spaz out," sending tanks flying across the map. The glitch appeared on maps like Kharkov and Pearl River.

### Accelerated Back Hopping (Half-Life 2)
ABH is the main speedrunning movement technique in Source engine games. It works because Valve's speed cap applies force opposite to your *viewing* direction rather than your *movement* direction. When moving backwards while jumping, the game's attempt to slow you down actually accelerates you exponentially. After just 2 jumps, players reach 1333 units per second. This glitch was intentionally left in single-player by Valve and is used extensively in speedruns like "Half-Life 2 Done With a High Magnitude of Velocity."
