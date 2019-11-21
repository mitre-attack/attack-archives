# attack-archives

attack-archives stores previous ATT&CK releases as seen in the [previous versions feature of the ATT&CK website](https://attack.mitre.org/resources/previous-versions/). The ATT&CK website build script pulls the content of this repo to build the previous versions pages.

[See the main ATT&CK website repository for more information about the ATT&CK website](https://github.com/mitre-attack/attack-website).

## archive_cli.py

The script `archive_cli.py` can be used to preserve the current state of the ATT&CK website as a named previous version. Run `python3 archive_cli.py -h` for usage instructions.

## archives.json

The `archives.json` file contains data about preserved versions. It is used to build [the index of previous versions on the ATT&CK website](https://attack.mitre.org/resources/previous-versions/). `archives.json` is automatically updated when the `archive_cli.py` script is run.

## archived version folders

The various folders in this repository each store a preserved version of the ATT&CK website. They are built to the `/previous/` route of the ATT&CK website. For example, a folder named `january1970` would be built to `https://attack.mitre.org/previous/january1970/`. 

## Related MITRE Work

#### ATT&CK
ATT&CK<sup>™</sup> is a curated knowledge base and model for cyber adversary behavior, reflecting the various phases of an adversary’s lifecycle and the platforms they are known to target. ATT&CK is useful for understanding security risk against known adversary behavior, for planning security improvements, and verifying defenses work as expected.

https://attack.mitre.org

#### CTI
[Cyber Threat Intelligence repository](https://github.com/mitre/cti) of the ATT&CK catalog expressed in STIX 2.0 JSON.

## Notice

Copyright 2019 The MITRE Corporation

Approved for Public Release; Distribution Unlimited. Case Number 18-3139

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

This project makes use of ATT&CK<sup>™</sup>

[ATT&CK Terms of Use](https://attack.mitre.org/resources/terms-of-use/)
