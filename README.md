# Hanwha

Public repo for Hanwha org and sharing

## What files are here?

The standard code of conduct and pull request templates are hosting in this special repository. These settings apply to all
of the repos in the htaic github org.

## What are the pipelines here

The pipelines contained in .github/workflows can be called from the workflow-templates defined in the repository.

### docker-env-release.yaml

This pipeline will release a docker image to an eks cluster.

### npm-build.yml

This pipeline will build a library/package for npm. It also contains jest and playwrite tests.
This pipeline also contains and runs semantic versioning.

### npm-codescan.yaml

This pipeline will perform audit and linting rules

### npm-codescan-complete.yaml

This pipeline will perform audit, linting, jest and playwrite tests.

### npm-docker-build.yaml

This pipeline will build a docker image that can run npm source via npm or python http service.

## Contributing

Pull requests are welcome. For major changes, please open a Jira DEVO ticket first to discuss what you would like to change.

Please make sure to update tests as appropriate.
