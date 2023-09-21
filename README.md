# Description

Created a custom JSON API that overrides the standard JSON library

# Installation

Download the .tar file from Github and unpack using the tar -xvf jsonapi...tar.gz command

# Dev Mode

In the root directory, run : pip install -e

# Examples

from jsonapi import jsonapi
complex_serialized = jsonapi.dumps(complex(2,3))
complex_deserialized = jsonapi.loads(complex_serialized)
