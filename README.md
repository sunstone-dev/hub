# Hub

This is [Sunstone](https://about.sunstone.dev) repository that contains aliases to remote public templates. Main Sunstone cluster at `https://sunstone.dev` is periodically synchronizing to this repository to update its aliases. 

## Distributed by default

Sunstone was designed and built to never rely on a single source of truth as it makes the system slow to adapt and usually costs people time to pass some review process before they can start using their own templates/charts. With Sunstone, alias repository is completely optional and instead of using **sunstone.dev/keel** you can just use **sunstone.dev/raw.githubusercontent.com/keel-hq/keel/master/deployment/deployment-template.yaml** without any additional configuration. 

This registry is purely for convenience.

## Contributing your own aliases

This project accepts contributions. To contribute:

1. Fork this repository
2. Add your own aliases following example in repositories.yaml file
3. Open a pull request with your change