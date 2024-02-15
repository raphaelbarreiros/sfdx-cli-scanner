Docker images: https://hub.docker.com/r/raphaelbarreiros/sfdx-cli-scanner

Based on:
https://github.com/salesforcecli/cli /
https://hub.docker.com/r/salesforce/cli

Contains most of the plugins and libraries from https://github.com/salesforcecli/status

2 build flavors

    slim : just the CLI installed from its tarballs, which includes its own bundled nodejs.
    full : a full node LTS installation, with sf installed as an npm package, along with openjdk-11-jdk-headless to simplify setup for VSCode Remote.
