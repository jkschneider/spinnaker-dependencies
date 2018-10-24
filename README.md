Spinnaker Dependencies
======================
[![Build Status](https://api.travis-ci.org/spinnaker/spinnaker-dependencies.svg?branch=master)](https://travis-ci.org/spinnaker/spinnaker-dependencies)

Manages common dependencies for Spinnaker components.

The ``src/spinnaker-dependencies.yml`` is parameterized with versions from the spring platform BOM to generate ``build/spinnaker-dependencies.yml``.

The ``build/spinnaker-dependencies.yml`` is published as an artifact to the bintray Spinnaker repo.

To generate a new version run:

````
./gradlew updateDependencies
````

