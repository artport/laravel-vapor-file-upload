# Laravel Vapor File Upload

This repository contains an alternative, dependency-free implementation of Laravel Vapor's S3 JavaScript package. Use it to stream file uploads to an S3 bucket just as you would using the original.

## Installation

Simply add the package to `package.json` like so:

```bash
"devDependencies": {
    "alpine-fetch": "github:artport/laravel-vapor-file-upload"
},
```

Then import the script into your application like so:

```js
import Vapor from '../../node_modules/laravel-vapor-file-upload/dist/laravel-vapor-file-upload.min.esm.js';
```
