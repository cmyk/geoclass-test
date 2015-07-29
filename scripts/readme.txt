This requires a preprocessing step to convert the YAML to JSON. A script is provided at scripts/yaml2mml.py, which depends on PyYAML, available through pip install pyyaml or packaged on Ubuntu as python-yaml.

After editing the YAML file, run ./scripts/yaml2mml.py < project.yaml > project.mml && touch project.mml to update the file and force TileMill to reload it.