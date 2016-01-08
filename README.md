# AWS CloudFormation YAML

A CloudFormation template in YAML format based on the excellent WordPress template by [widdix](https://github.com/widdix/aws-cf-templates).

## Usage

Before usage, first convert from YAML to JSON which can be done in variety of ways, this is just one example in Python to get you going:

    #!/bin/bash
    python -c 'import sys, yaml, json; json.dump(yaml.load(sys.stdin), sys.stdout, indent=2)' < $1.yaml > $1.json

Simply store in an executable shell script and run as:

    yaml2json wordpress

Easy..

