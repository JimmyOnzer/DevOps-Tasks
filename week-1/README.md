## 1 What is your understanding of a DevOps Culture in an Organization

Devops culture represent a change of mindset, a change in your software architecture, a change in your network, a change in your processes, a change in the technologies, and also a change in the people. Devops culture establish a new way to do teamwork for business growth. It is based on a shared understanding between developers and operations and a shared responsibility for the software they create. This means greater transparency, communication and collaboration in development. This helps companies align their people, processes, and tools toward a more unified customer focus. It invent a way for two different teams i.e development and operations to work together in coordination and with effective communication on the same project. It blurs the lines between developer, operator, and QA roles. Implementing DevOps requires significant changes in the way people work with each other and how organizations contribute to the necessary cultural change. Devops is neither a tool or a software it is a culture. It introduces a flow of value to an organization to an amazing world of best practices through test automation, continuous delivery, continuous deployment and monitoring and much more.

DevOps is a cultural view of how everyone works right. In the software-defined world, many questions arise. How to get your product to production quickly and when will it go into production? How do I know if I found the best solution? How quickly can I apply improvements and updates? DevOps seeks to engage everyone interested in the game and engage them early in the collaborative process. Achieving this success with DevOps starts with understanding the key business benefits. Organizations can run faster with less downtime and less security concerns.

Competition is fierce, and every company needs a technological advantage to get ahead. No matter your industry, the user experience is key for your customers. However, meeting that demand is difficult with siloed development methodologies. Instead, adopting a DevOps culture can focus disparate resources on a single goal to move that new idea to production in a flash.

Organization adopt devops culture because of:

- Performance optimization
- Shorter development circle
- Better overall efficiency
- Better team coordination
- Budget friendly

## 2 What Does a DevOps engineer do and what tools are available?

- Infra setups (either over Cloud or Bare Metal or VM)
- Software Installations
- Server Maintenance
- Application Support
- Version Control support (GIT, SVN …)
- Build and Release process support (Jenkins, Team city …)
- Automate Configuration Management (Ansible, Chef, Puppet ...)
- Support cross functional teams
- Research and Deploy new tools
- Vulnerability Assessment and Patching
- Server and Application level Monitoring (ELK, Prometheus, Grafana ...)
- Knowledge of Ticketing system (Jira, Bugzilla ...)
- Automated Backups
- Access management
- Documentation
- Continuous Improvement

## 3 Describe SDLC identifying where devOps fit in.

SDLC is a systematic software development process that ensures the quality and accuracy of the generated software. The SDLC process aims to create high-quality software that meets customer expectations. System development must be completed within a set time and cost. SDLC consists of detailed plans that describe how to plan, deploy, and maintain specific software. Each stage of the SDLC lifecycle has its own processes and outputs that are used in the next stage. SDLC stands for Software Development Lifecycle, also known as Application Development Lifecycle.

- Prior to DevOps, we had this waterfall model of software development. This model was a straightforward and a linear model that followed a top down approach. it had various phases starting with requirement gathering and analysis. In this phase, you gather the requirements from the client for developing an application, and then you analyze those requirements. Once you're clear with the requirements, you proceed further with the design phase. In this phase, you think about how the software is going to look like and you prepare a blueprint of the software. The next phase is the implementation phase, where you begin the coding of the application. Once the application is developed, it is tested in the verification phase. After testing, the application is deployed. On the production servers. And once the application goes live, it is monitored in the maintenance phase. This wasn't a perfect model. Since it had a few drawbacks. One of the drawbacks of this model is unless you complete a particular stage, you cannot proceed to the next stage. This was a very time consuming model. This model was suitable only for projects where requirements are stable. By stable I mean the requirements will not change with the time. But in today's world, this is a very unlikely scenario, because requirements keep on changing. No working software is delivered until the final stage of the waterfall model. Also this model was not suitable for large projects and the object oriented projects. So these were a few drawbacks of the waterfall model.

- The next model is the Agile Model. In this model, the software is broken down into various iterations. Each iteration has various phases such as planning design, development, and so on. The duration of each iteration is generally two weeks to eight weeks. So what happens in Agile Model is you release the software in the first iteration. After this you gather the feedback from the end users or the customers about the application and you try to incorporate those changes into the second iteration. And then you again release the software into the market which is the second iteration, you again repeat the same procedure and then you release the software again, which is a third iteration and so on. So this model was better than the previous model. But this model two had a few drawbacks. While this model brought agility to the development team, the operations team still did not come up to speed with the development team. Because of this, there was constant conflict between the development team and the operations team. This conflict hampered the pace of the software development and the release.

DevOps begins where Agile stops. It basically takes all the developed products and gets them where they need to be. The DevOps lifecycle optimizes development processes from start to end and engages the organization in continuous development, resulting in faster delivery times. This process mainly consists of the following seven stages.

- Continuous development
- Continuous integration
- Continuous testing
- Continuous deployment
- Continuous monitoring
- Continuous feedback
- Continuous operations

## 4 What are the devOps best practices.

1 Practice agile methodology: Following the agile methodology, teams divide work into small chunks. It allows them to deliver small but incremental features fast, which lays the basis for DevOps’ continuous deployment practice.
2 Continuously automate processes: Automation accelerates the development cycle by reducing the amount of manual work. It helps you push code in production more frequently and produce consistent, reliable, and safe software.
3 Continuous Integration Practices for DevOps:

- Maintain a single source repository
- Automate the build process
- Make the build self-testing
- Commit to the mainline daily
- Trigger a build after every commit
- Test in a clone of the production environment
- Make fast feedback on quality available to everyone
- Make fixing broken builds a priority task

4 Collaborative Culture Practices for DevOps: DevOps is a culture, not a role. Adopting DevOps practices requires creating an environment for cross-team communication and collaboration. When introducing DevOps culture, you’ll work on:

- Building trust and transparency between development and operations
- Instilling an attitude of shared responsibility and ownership
- Promoting customer-centricity and empathy across teams

5 Continuous Monitoring: Ensure applications have adequate monitoring, often automated, that allows teams to proactively identify difficulties with production code.

6 Automate dashboards to allow all team members and leadership to quickly identify bottlenecks and dive deeper into any roadblocks. (Jira and Xray dashboards show you key Quality metrics like requirements traceability, requirements coverage, and overall test coverage)

7 Continuous Testing:

- Treat Test Code as Code
- Treat Test Code as Code
- Provide Fast Feedback
- Generate and Maintain Test Data
- Test resources are scaled automatically according to the resource requirements of specific tests selected and the available time for testing.
- Make automation a priority

8 Continuous Security:

- Developers are empowered and trained to take personal responsibility for security.
- Security assurance automation and security monitoring practices are embraced by the organization.
- All information security platforms that are in use expose full functionality via APIs for automation capability.
- Proven version control practices and tools are used for all application software, scripts, templates and blueprints that are used in DevOps environments.
- Immutable infrastructure mindsets are adopted to ensure production systems are locked down.
- Security controls are automated so as not to impede DevOps agility.
- Security tools are integrated into the CI/CD pipeline.
- Source code for key intellectual property on build or test machines are only accessible by trusted users with verified credentials.

## 5 What are the differences between a devOps engineer and SRE.

| DevOps Engineer                                                                                                                                                                 | SRE                                                                                                                                                                                                             |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DevOps is an approach to culture, automation, and platform design intended to deliver increased business value and responsiveness through rapid, high-quality service delivery. | SRE can be considered an implementation of DevOps.                                                                                                                                                              |
| DevOps aims to handle runtime errors and allow teams to learn from them                                                                                                         | SRE enforces error management through Service Level Commitments (SLx) to ensure all failures are handled.                                                                                                       |
| DevOps gathers metrics through a feedback loop                                                                                                                                  | On the other hand, SRE enforces measurement by providing SLIs, SLOs, and SLAs to perform measurements. Since Ops are software-defined, SRE monitors toil and reliability, ensuring consistent service delivery. |
| DevOps Engineers are ops-focused engineers who solve development pipeline problems                                                                                              | Site Reliability Engineers are development-focused engineers who solve operational/scale/reliability problems                                                                                                   |
