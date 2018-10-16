# external-config-example

If you want to share your `screwdriver.yaml` amongst many Screwdriver pipelines, you can use the [external config feature](https://docs.screwdriver.cd/user-guide/configuration/externalConfig).

In this example, this repository contains the external config, which controls "child pipelines" listed under `childPipelines` -> `scmUrls` (`git@github.com:screwdriver-cd-test/external-config-child1.git` and `git@github.com:screwdriver-cd-test/external-config-child2.git`).
