# Threejs Controls as modules using UMD (Universal Module Definition)

This project aims to make it easier to work with controls as modules instead of having to manually copy the files from the examples/controls folder.

#### Install

```sh
npm i --save threejs-controls
```
or
```sh
yarn add threejs-controls
```

### Usage


#### AMD

```js
define(['threejs-controls/EditorControls'], function(EditorControls) {
    var control = new EditorControls(parameters);
});
```

#### CommonJS

```js
var EditorControls = require('threejs-controls/EditorControls');
var control = new EditorControls(parameters);
```

#### ES6 imports

```js
import EditorControls from 'threejs-controls/EditorControls';
const control = new EditorControls(paramenters);
```


### Includes

* DeviceOrientationControls
* DragControls
* EditorControls
* FirstPersonControls
* FlyControls
* OrbitControls
* OrthographicTrackballControls
* PointerLockControls
* TrackballControls
* TransformControls
* VRControls

### Tested Controls

* EditorControls
* OrbitControls
* TrackballControls
* TransformControls

### TODO

* Test the remaining controls
