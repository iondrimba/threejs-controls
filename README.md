# Threejs Controls as UMD modules

This project aims to make it easier to work with controls as modules instead of having to manually copy the files from the examples/controls folder

### Usage


#### AMD

```
define(['threejs-controls/EditorControls'], function(EditorControls){
    var control = new EditorControls(parameters);
});

```

#### CommonJS

```
var EditorControls = require('threejs-controls/EditorControls');
var control = new EditorControls(parameters);

```

#### ES6 imports

```
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

### TODO

* Test the remaing controls
