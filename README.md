# Probate Cron Helm Chart

Helm chart for the Probate kubernetes cron job. It uses the [probate-back-service](https://github.com/hmcts/probate-back-service) image to execute scheduled tasks by passing the arguments: `run [taskname]` to the jar.
