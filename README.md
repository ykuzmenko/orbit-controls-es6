# Orbit Controls ES6

Little update to Orbit Controls from three.js to support ES6 modules

## Install
`npm i orbit-controls-es6 --save`


## Example
```js
import OrbitControls from 'orbit-controls-es6';

const controls = new OrbitControls(camera, renderer.domElement);
controls.enabled = true;
controls.maxDistance = 1500;
controls.minDistance = 0;
```

## Multivalue config
```
controls.mouseButtons = {ORBIT: [THREE.MOUSE.LEFT, THREE.MOUSE.RIGHT], ZOOM: THREE.MOUSE.MIDDLE, PAN: null};
```

