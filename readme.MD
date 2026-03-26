## GitHub Actions

1. name: HelloWorld
This is the workflow title. It helps identify your workflow in the GitHub Actions UI.

2. on: [push]
Defines the event(s) that trigger the workflow.
Can be: push, pull_request, workflow_dispatch (manual), schedule (cron), etc.

3. jobs
Contains all tasks/stages in the workflow.
Each job runs on a runner independently.

4. simple-job
The job name. You can have multiple jobs in one workflow.

5. runs-on: ubuntu-latest
Specifies the runner/agent for the job. GitHub provides Ubuntu, Windows, or macOS runners.

6. steps
Each step is an action or command executed in sequence.

7. - name: step-1 / step-2
Optional step name to make the workflow readable.
run: executes shell commands inside the runner.