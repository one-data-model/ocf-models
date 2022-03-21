# ocf-models

OCF convered oneDM data models.

The original repo is located at: https://github.com/openconnectivityfoundation/IoTDataModels

The original content as website is at: https://openconnectivityfoundation.github.io/devicemodels/docs/index.html

## SDF model overview

http://onedm.org/ocf-models/tools/resource.html

## changes

The RT value of the OCF model is translated into the filename.

- The oic.r prefix is removed
- The periods "." are replaced with underscores "_"

Examples:

| resource type  |  sdf file name  |
|----------------| --------------- |
| oic.r.batterymaterial | sdfobject-batterymaterial.sdf.json |
| oic.r.body.water | sdfobject-body_water.sdf.json |

Validation: [![CI](https://github.com/one-data-model/ocf-models/actions/workflows/ci.yml/badge.svg
)](https://github.com/one-data-model/ocf-models/actions/workflows/ci.yml) — please check the
build log linked through this badge for CI messages.
