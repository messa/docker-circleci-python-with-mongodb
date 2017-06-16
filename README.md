Docker image circleci/python with MongoDB
=========================================

Usage
-----

In your `.circleci/config.yml`:

```yaml
jobs:
    build:
        docker:
            - image: messa/circleci-python-with-mongodb:3.6
```

Available tags:

- `messa/circleci-python-with-mongodb:latest`
- `messa/circleci-python-with-mongodb:3.6`
- `messa/circleci-python-with-mongodb:3.5`
- `messa/circleci-python-with-mongodb:3.4`
