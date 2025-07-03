# Senior Python Developer, [Yields.io]{{ urls.work.yields }}

_December 2019 &ndash; August 2020, Brussels, Belgium (remote)_

???+ summary

    - Worked on the core of the platform as the primary Python developer.
    - Refactored and stabilized the codebase, added thousands of tests, fixed bugs, and developed new features.
    - Worked on automatically migrating and testing client code and artifacts with version increases, and deprecated old features.
    - Moved integration tests away from depending on mocks into tests that worked with a deployed Docker environment.

Yields.io is the first company to develop an AI-based automated model risk management system on an enterprise-wide scale
with a platform designed to support the full model life cycle.
They mostly offer their services to the financial sector, with smaller, regional banks automating the model validation effort,
and larger institutions streamlining and scaling their models.

I was the primary Python developer at Yields.
The core of the platform is written in Python, and communicates with a backend API written in Scala.
Jupyter is used by the clients in order to run their algorithms. I refactored and stabilized the codebase, added tests, fixed bugs,
developed new features that the company or clients requested, and added client-facing Jupyter notebooks.

For example, I split what was a monolith into three separate packages which could be deployed independently.
This also allowed clients to implement their own algorithm using our platform as a base in case they wanted to keep them proprietary.

In addition, I used pytest to write thousands of unit tests for previously untested code,
and refactored individual functions to be more testable.
This enabled us to catch new bugs and identify areas where the functionality differed from the design.

I worked on automatically migrating and testing client code and artifacts with version increases, and deprecated old features.
I also helped coworkers when they had questions about parts of the codebase.

Towards the end, I was moving integration tests away from depending on mocks which did not track changes to the API,
into tests that could work with a deployed Docker environment.
