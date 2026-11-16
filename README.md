Open-source maintainer. [Open edX](https://openedx.org) core contributor since 2019;
I keep Python and Django ecosystems upgraded at scale and measure whether they stay healthy.

### [OSSvitals](https://ossvitals.org)

[![GitHub last commit](https://img.shields.io/github/last-commit/UsamaSadiq/OSSvitals?style=flat-square)](https://github.com/UsamaSadiq/OSSvitals/commits)
[![License](https://img.shields.io/github/license/UsamaSadiq/OSSvitals?style=flat-square)](https://github.com/UsamaSadiq/OSSvitals/blob/main/LICENSE)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fossvitals.org&style=flat-square&label=ossvitals.org)](https://ossvitals.org)

My main project. Daily health dashboards for open-source organizations, built from public data
on a published method; the successor to the Open edX Repo Health Dashboard.

* [Open edX](https://openedx.ossvitals.org): every repository graded daily on maintenance health
* [Moneta](https://moneta.ossvitals.org): how far each fork has drifted from its upstream, with releases and security advisories
* Read-only MCP endpoint at `mcp.ossvitals.org`, so AI agents can query the same data
* Proposed by Axim as Open edX's official maintenance-tracking tool, replacing Backstage ([DEPR](https://github.com/openedx/public-engineering/issues/576))

Code: [UsamaSadiq/OSSvitals](https://github.com/UsamaSadiq/OSSvitals)

### Projects I maintain or co-maintain

| Project | Python versions | Release | Released | Last commit | Monthly downloads |
| :--- | :--- | :--- | :--- | :--- | :--- |
| [django-config-models](https://github.com/openedx/django-config-models) | [![Supported Python versions](https://img.shields.io/pypi/pyversions/django-config-models.svg?style=flat-square&label=)](https://pypi.org/project/django-config-models/) | [![PyPI version](https://img.shields.io/pypi/v/django-config-models?style=flat-square&label=)](https://pypi.org/project/django-config-models) | [![GitHub release date](https://img.shields.io/github/release-date/openedx/django-config-models?style=flat-square&label=)](https://github.com/openedx/django-config-models/releases) | [![GitHub last commit](https://img.shields.io/github/last-commit/openedx/django-config-models?style=flat-square&label=)](https://github.com/openedx/django-config-models/commits) | [![PyPI downloads](https://static.pepy.tech/personalized-badge/django-config-models?period=monthly&units=ABBREVIATION&right_color=GREEN&left_text=%E2%A4%93)](https://pepy.tech/projects/django-config-models) |
| [django-user-tasks](https://github.com/openedx/django-user-tasks) | [![Supported Python versions](https://img.shields.io/pypi/pyversions/django-user-tasks.svg?style=flat-square&label=)](https://pypi.org/project/django-user-tasks/) | [![PyPI version](https://img.shields.io/pypi/v/django-user-tasks?style=flat-square&label=)](https://pypi.org/project/django-user-tasks) | [![GitHub release date](https://img.shields.io/github/release-date/openedx/django-user-tasks?style=flat-square&label=)](https://github.com/openedx/django-user-tasks/releases) | [![GitHub last commit](https://img.shields.io/github/last-commit/openedx/django-user-tasks?style=flat-square&label=)](https://github.com/openedx/django-user-tasks/commits) | [![PyPI downloads](https://static.pepy.tech/personalized-badge/django-user-tasks?period=monthly&units=ABBREVIATION&right_color=GREEN&left_text=%E2%A4%93)](https://pepy.tech/projects/django-user-tasks) |
| [edx-rest-api-client](https://github.com/openedx/edx-rest-api-client) | [![Supported Python versions](https://img.shields.io/pypi/pyversions/edx-rest-api-client.svg?style=flat-square&label=)](https://pypi.org/project/edx-rest-api-client/) | [![PyPI version](https://img.shields.io/pypi/v/edx-rest-api-client?style=flat-square&label=)](https://pypi.org/project/edx-rest-api-client) | [![GitHub release date](https://img.shields.io/github/release-date/openedx/edx-rest-api-client?style=flat-square&label=)](https://github.com/openedx/edx-rest-api-client/releases) | [![GitHub last commit](https://img.shields.io/github/last-commit/openedx/edx-rest-api-client?style=flat-square&label=)](https://github.com/openedx/edx-rest-api-client/commits) | [![PyPI downloads](https://static.pepy.tech/personalized-badge/edx-rest-api-client?period=monthly&units=ABBREVIATION&right_color=GREEN&left_text=%E2%A4%93)](https://pepy.tech/projects/edx-rest-api-client) |
| [pytest-repo-health](https://github.com/openedx/pytest-repo-health) | [![Supported Python versions](https://img.shields.io/pypi/pyversions/pytest-repo-health.svg?style=flat-square&label=)](https://pypi.org/project/pytest-repo-health/) | [![PyPI version](https://img.shields.io/pypi/v/pytest-repo-health?style=flat-square&label=)](https://pypi.org/project/pytest-repo-health) | [![GitHub release date](https://img.shields.io/github/release-date/openedx/pytest-repo-health?style=flat-square&label=)](https://github.com/openedx/pytest-repo-health/releases) | [![GitHub last commit](https://img.shields.io/github/last-commit/openedx/pytest-repo-health?style=flat-square&label=)](https://github.com/openedx/pytest-repo-health/commits) | [![PyPI downloads](https://static.pepy.tech/personalized-badge/pytest-repo-health?period=monthly&units=ABBREVIATION&right_color=GREEN&left_text=%E2%A4%93)](https://pepy.tech/projects/pytest-repo-health) |
| [edx-repo-health](https://github.com/openedx/edx-repo-health) | | | | [![GitHub last commit](https://img.shields.io/github/last-commit/openedx/edx-repo-health?style=flat-square&label=)](https://github.com/openedx/edx-repo-health/commits) | |

Ecosystem work:

* Python 3.8 → 3.12 and Django 3.2 → 4.2 → 5.2 upgrades across 150+ Open edX repositories, with reusable codemods
* Travis / Jenkins / CircleCI → GitHub Actions migrations, self-hosted autoscaling runners on EKS
* Kafka event-bus external grading for Open edX (Axim-funded, shipped in the Ulmo release)
* 800+ merged PRs across 140+ Open edX repositories (including retired ones), 5,600+ PRs reviewed
* eMudhra CA key-compromise response (Oct 2026): drove the certifi / uv / pip upgrade across every backend Open edX repository, 118 PRs in 82 repos, with security releases ready within 48 hours of disclosure

Upstream, outside Open edX ([live board](https://github.com/users/UsamaSadiq/projects/1) of issues and PRs, including the open ones):

* [tox](https://github.com/tox-dev/tox/pull/1682) and [virtualenv](https://github.com/pypa/virtualenv/pull/1953): `importlib-metadata` constraints (2020)
* [algoliasearch-django](https://github.com/algolia/algoliasearch-django/pull/316) and [django-cache-memoize](https://github.com/peterbe/django-cache-memoize/pull/51): Django 3.2 test matrices (2021)
* [swagger2rst](https://github.com/Arello-Mobile/swagger2rst/pull/11): PyYAML `FullLoader` fix (2021)
* [python-cloudflare](https://github.com/cloudflare/python-cloudflare/pull/156): drop the `future` dependency (2023)
* [Penpot](https://github.com/penpot/penpot/pull/13052): fix the backend database pool `min-size` regression and document the pool settings (2026)

Blog and talks: [usamasadiq.us](https://usamasadiq.us)

Talks:

* [Elevating Open edX Development: The Repo Health Dashboard](https://www.youtube.com/watch?v=kbt5n8Erv-s), Open edX Conference 2024
* [Observe, Connect, Act: an agent loop for open source maintenance](https://lahore.aitinkerers.org/connect/mu_EvYzH0aDV2c/presenters), AI Tinkerers Lahore, October 2026
