# base-terrain-feature-whales

The `Whales` terrain feature: a special resource a square can hold.

For example: Civ2's Whales, found on Ocean.

This package only declares the class: it has no `main` and registers nothing, so installing it changes no game.
A game's rules register it and give it its yields.

```ts
import Whales from '@civ-clone/base-terrain-feature-whales/Whales';
import { instance as availableTerrainFeatureRegistryInstance } from '@civ-clone/core-terrain-feature/AvailableTerrainFeatureRegistry';

availableTerrainFeatureRegistryInstance.register(Whales);
```

Part of the Civ2 work (civ-clone/web-renderer#1008).
