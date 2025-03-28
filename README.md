# jenkins

Jenkins is a CI/CD Framework which plays a very important role in software industry.

    Using jenkins and with UI we will use this to run our jobs or to schedule our jobs.

Installing Linux:
    > https://www.jenkins.io/doc/book/installing/linux/
    > https://www.jenkins.io/doc/book/installing/linux/#red-hat-centos

Server Requirements:
    > t3.medium, spot , 30gb storage

> Jenikins is all about jobs and we a job means the list of tasks to be executed.

    Jenkins offers multiple types of jobs:
        1) Freestyle jobs ( Options of the jobs are created manually )
        2) Pipeline Jobs ( All the options are handled in the form of code) : Preferred and closed to GitOps Culture.

> Jenkins run as a standalone server and cannot be operated as a CLUSTER. But we will diversify the jobs by running them on agents.

    To run jobs on the top of a node/agent, agent should have java installed.

Demonstrate adding workStation as an agent to the controller.

> To write a pipeline, fileName should suffixed with Jenkinsfile

Remembers, stages in jenkins are sequence in nature, STATE-1 will only be executed if the STAGE-1 is completed. 
But, we can achive parallel processing using PARALLEL Stages.