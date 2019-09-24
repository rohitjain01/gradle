## Create a build scan

Follow these simple steps to create a build scan:

1. Clone this project
1. Run `./gradlew build --scan`
1. Agree to the [Terms of Service][terms-of-service] on the command line

The build should end with something similar to:

    Publishing build scan...
    https://gradle.com/s/ria2s2x5oaazq

Follow the green link shown at the end of the build to view your build scan.

Note: If you run a build without the `--scan` flag, no build scan will be created and
no information will be sent.
