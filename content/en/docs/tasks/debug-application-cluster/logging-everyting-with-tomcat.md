---
title: Logging everything with tomcat
reviewers:
- chenopis
content_template: templates/task
toc_hide: true
---

{{% capture overview %}}

This page shows how to log with a container that does not respect [rule XI. Logs](https://12factor.net/logs)

{{% /capture %}}

{{% capture prerequisites %}}

{{< include "task-tutorial-prereqs.md" >}} {{< version-check >}}

{{% /capture %}}

{{% capture steps %}}

## Package the legacy application

In this exercise, you create a Pod using an existing Container and stream all logs to `stdout`.
The Image is packaged with a legacy `java` application deployed in a `tomcat`. Logs are rotated from inside the Container.

{{% /capture %}}

{{% capture discussion %}}

## Understanding ...
**[Optional Section]**

Here's an interesting thing to know about the steps you just did.

{{% /capture %}}

{{% capture whatsnext %}}

**[Optional Section]**

* Learn more about [Writing a New Topic](/docs/home/contribute/write-new-topic/).
* See [Using Page Templates - Task template](/docs/home/contribute/page-templates/#task_template) for how to use this template.

{{% /capture %}}


