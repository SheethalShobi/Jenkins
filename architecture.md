## Core Concepts
The following are some important concepts of Jenkins:

### 1. Jenkins Controller(Formerly Master)
The Jenkins Controller serves as the central system for managing a Jenkins instance, often referred to as its "heart." It oversees agents and their connections, determining the tasks they should perform. Additionally, the Jenkins Controller loads plugins and ensures that jobs run in the correct sequence.

### 2. Jenkins Agent(Formerly Slave)
Jenkins Agent is a machine that performs tasks like running scripts, executing tests, or building components, etc. These tasks are assigned by the Jenkins Controller. Each agent can have its setup, like different operating systems, software, or hardware. This helps Jenkins handle many types of tasks and work faster by spreading the load.

There are two main types of agents:

Permanent Agents: These are always ready and connected to Jenkins. They’re like dedicated workers who are always on standby.
Ephemeral Agents: These are temporary. Jenkins starts them only when needed, usually in the cloud or using tools like Docker. When the job is done, they’re shut down.
jenkins_master
### 3. Jenkins Node
A Jenkins Node is a term that is used in Jenkins 2.0 to mean any system that can run Jenkins jobs. This is mainly used in Controllers and Agents and sometimes used instead of those terms. A node is a machine that Jenkins uses to run jobs like building and testing projects. If a node isn’t performing well or its health drops below a certain threshold level, Jenkins will take that node offline to prevent any problems.

### 4. Jenkins Job
Jenkins jobs are used to perform the work in the Jenkins system. A jenkins jobs is an automated job that you set up in jenkins to do things like build, test or deploy your code. Instead of doing these steps manually every time, Jenkins can do them for you whenever there’s a change in your code. This helps save time and reduces mistakes.

### 5. Jenkins Plugins
Jenkins provides 2000+ community contributed Jenkins plugins which developers can use for building, deploying and automating any project. You can connect to GitHub, Slack, AWS, Docker, and more—instantly amplifying Jenkins’ power.. You can easily install and upgrade these available plugins easily from the Jenkins Dashboard.

### 6. Jenkins Pipeline
DevOps professionals mostly work with pipelines because pipelines can automate the processes like building, testing, and deploying the application. With the help of Continuous Integration / Continuous Deployment (CI/CD) Pipeline scripts we can automate the whole process which will increase productivity and save lots of time for the organization and can deliver quality applications to the end users.
