## Welcome to "Hello World" with GitHub Actions

This course will walk you through writing your first action and using it with a workflow file. 

**Ready to get started? Navigate to the first issue.**

# About Github Actions

- jobs: is the base component of a workflow run
- build: is the identifier we're attaching to this job
- name: is the name of the job, this is displayed on GitHub when the workflow is running
- steps: the linear sequence of operations that make up a job
- uses: actions/checkout@master uses an action called checkout to use a copy of our code - repository
- uses: ./action-a uses an action named action-a by referencing the path to the action's - directory, relative to our repository
- env: is used to specify the environment variables that will be available to your action in the runtime environment. In this case, the environment variable is MY_NAME, and it is currently initialized to "Mona".