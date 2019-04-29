# graphene_django_helpers package

**Helpers for graphene-django**

[![CircleCI](https://circleci.com/gh/mrmilu/graphene-django-helpers.svg?style=svg)](https://circleci.com/gh/mrmilu/graphene-django-helpers)
[![codecov](https://codecov.io/gh/mrmilu/graphene-django-helpers/branch/master/graph/badge.svg)](https://codecov.io/gh/mrmilu/graphene-django-helpers)

## Requirements

- Python 3.4, 3.5, 3.6, 3.7
- Django 2.0, 2.1, 2.2
- Graphene 2.1.x
- Django Graphene 2.2.x

## Testing

```bash
$ cd docker/graphene_django_helpers
$ docker-compose run app
```

Command to run a bash console tu run pytest manually
```bash
$ cd docker/graphene_django_helpers
$ docker-compose run --rm --service-ports app bash
$ cd /src

# Normal tests
$ pytest

# Tests with coverage
$ pytest --cov=graphene_django_helpers tests/
$ coverage html
$ cd htmlcov
$ python3 -m http.server
```

###### Sponsored by https://mrmilu.com
