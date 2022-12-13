# Prl Cron Helm Chart

Helm chart for the Prl kubernetes cron job. It uses the [prl-cos-api](https://github.com/hmcts/prl-cos-api) image to execute scheduled tasks by passing the arguments: `run [taskname]` to the jar.
