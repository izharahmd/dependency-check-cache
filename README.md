# dependency-check-cache

A docker container image over [owasp/dependency-check](https://hub.docker.com/r/owasp/dependency-check) which is updated daily to cache latest CVE and CPE data files. Helps in reducing CI time.  

The image is hosted at [izhar0407/dependency-check](https://hub.docker.com/r/izhar0407/dependency-check).

## Usage
Refer [jeremylong/DependencyCheck](https://github.com/jeremylong/DependencyCheck)

## Note
Since the image is updated at the interval of 4 hours daily, use option `--noupdate` while running scan to disable automatic updates.