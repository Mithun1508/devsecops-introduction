An Introduction to DevSecOps for Beginners

Invicti Web Application Security Scanner – the only solution that delivers automatic verification of vulnerabilities with Proof-Based Scanning™.


DevOps has been a success in the past few years. It has now become one of the core practices in every organization. Bringing collaboration between development and operation teams has helped organizations launch their products at speed with higher quality.

By using DevOps tools and practices, most of the things have got smoother and automated.

But do you think there is no challenge with DevOps?

There is!

Why do we need DevSecOps?
Forrester research showed that 58% of companies had a data breach, and 41% of those come from software vulnerabilities. Security mistakes have the potential to cause considerable harm and cost organizations in millions.

88% growth and application vulnerabilities in over two years

78% of vulnerabilities are found in indirect dependencies

37% of open source developers do not implement any security during continuous integration

54% of developers don’t do any docker image security testing

Earlier in the waterfall model, you used to gather all the requirements, work on all the requirements, and then after months or years, you used to deliver the complete product. In DevOps, the complete product is released iteratively. An application can have hundreds of iteration in a day, but would a penetration tester be able to find security flaws in an application a hundred times a day?

The answer is No!

Developers, admins, architects think if they are working on the cloud, they are safe because the cloud provider is taking care of the security. This is a myth and not true. Most of the time, if you are working on the cloud, you are more exposed to attacks.

So in today’s time, security is a very important factor in every company. Traditional security is not good enough to keep up with the rapid pace of DevOps.

This is where DevSecOps comes to rescue!

What is DevSecOps?
DevSecOps is security as a code culture where you integrate security tools in the DevOps lifecycle. Security as a part of the DevOps process is the only way to mitigate the risks.

It is a transformational shift that incorporates security culture, practices, and tools in each phase of the DevOps processes. It removes the silos between development, security, and operations team.

![devsecops](https://user-images.githubusercontent.com/93249038/221332892-63d608c2-8491-40ae-945b-b94e822a7d23.jpg)

DevSecOps
It follows the shift-left approach, which means injecting security processes early into the design/plan stage to provide security awareness to development and operations teams and fulfill the cybersecurity requirements.

These are the practices of how DevSecOps is being implemented:

Collaborating with security and development teams on the threat model
Integrating security tools in the development integration pipeline
Prioritizing the security requirements as a part of the product backlog
Reviewing infrastructure-related security policies before deployment
Security experts are evaluating automated tests.
Modern technology innovation plays a vital role in DevSecOps. Security as a code, Compliance as a code, and Infrastructure as a code can eliminate many manual security activities and boost the overall efficiency.

## Tools for DevSecOps
It requires many technology stacks with several solutions that need to be carefully integrated to deploy the DevSecOps culture without creating gaps or creating bottlenecks in security.

Below are some important and trending DevSecOps tools:

1 SonarQube: used for continuous inspection for code quality. It provides continuous feedback on software quality.

2 ThreatModeler: provides a threat modeling solution that scales and secures the enterprise software development lifecycle. It predicts, identifies, defines security threats, and helps you in saving time and cost.

3 Aqua Security: provides prevention, detection, and response automation to secure the build, secure cloud infrastructure, and secure running workloads. It secures the entire application lifecycle.

4 CheckMarx: a complete suite of software security solutions. This suite provides security testing for static and dynamic applications, tools like software composition analysis, and code bashing to promote software security culture among developers.

5 Fortify: provides application security as a service. It is used majorly in enterprise for Secure development, security testing, and continuous monitoring and protection.

6 HashiCorp Vault: manage secrets like passwords, tokens, API keys, certificates, and protect such sensitive data. There is more secret manager you can explore here.

7 GauntLT: a behavior-driven development tool to automate attack tools. It can easily integrate with your organization’s testing tool and processes.

8 IriusRisk: provides production-level application security at scale. It helps you manage threat models and security risks using two-way synchronization with testing tools and issue trackers with a real-time security activity view.

## DevSecOps Ecosystem
This is the flow of different phases in the DevSecOps ecosystem. Here security scanning will be a part of the complete ecosystem.

![2](https://user-images.githubusercontent.com/93249038/221332915-bc87bb37-b2f0-4d17-9c86-c26df7d3be5d.jpg)

devsecops pipeline

In the development phase, security tools and plugins can be integrated into the IDE environment directly, identifying any source code vulnerability.

You can integrate pre-commit hooks that will not allow committing any insecure data content like authentications keys to the repository and keep such data on the developer’s machine only.
Version control will maintain secret management and configurations at the repository level.

Pre and post-build will ensure static and dynamic code reviews, execution, and feedback.

QA environment will check for security scanning and especially third-party component scanning.

While the staging environment will execute vulnerability and penetration testing, the results will be shared with development, quality, and security teams.

Automated security scanning on the production environment for Infrastructure as a code, 
Compliance as a code and Security as a code will mitigate many manual security activities.

Finally, monitoring the environment will enable alerts and notifications for security thresholds.

Vulnerability management will be a part of the entire DevSecOps ecosystem.

## Conclusion
That was all about the basics of DevSecOps. If you are into DevOps, you must start promoting and applying DevSecOps culture in your organization. You can also check out this blog to understand the core responsibilities of a DevSecOps expert.
