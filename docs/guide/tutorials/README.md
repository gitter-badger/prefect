---
sidebarDepth: 0
---

# Contents

These tutorials are intended to help the reader get acquainted with the many features of Prefect and its vocabulary. All code examples
are locally executable in any Python version supported by Prefect (3.5+). Note that all features presented here are run without
the Prefect server.

## [ETL](etl.md)

The "hello, world!" of data engineering

## [Using Prefect as a Calculator](calculator.md)

Can your data engineering framework do this?

## [Triggers, Reference Tasks](triggers-and-references.md)

Overview of different triggers, such as `manual_only`, which allows for manual approval before a task can run. Also covered: determining flow states using `reference_tasks`

## [Flow Visualization](visualization.md)

Visualize your Prefect flows with `flow.visualize()`

## [Advanced Features](advanced-mapping.md)<Badge text="advanced" type="warn"/><Badge text="0.3.2+"/>

Dynamically create large numbers of tasks using `task.map()`! Using a real-world web-scraping project as an example, walks through the more advanced features of Prefect including advanced parameter usage, task mapping, and parallelism.

## [Prefect Slack Integration](slack-notifications.md)<Badge text="0.3.2+"/>

Install the Prefect Slack integration and get real time notifications on the state of your tasks and flows -- all within the convenience of Slack!
