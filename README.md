# Learning Kubernetes
I see Kubernetes (and similar technologies) bridging clients from 'on premises' to the cloud[1].  The learning plan I am looking at consists of 3 parts, training, certification, and a conference.  The goal being that I am certified prior to the conference.

## Notes:
This section divides up the topics contained within kubernetes into different areas of study.
 * [Docker Notes](docker/toc.md)
 * [Kubernetes Notes](k8s/toc.md)
 * [Azure Kubernetes Service (AKS) Notes](aks/toc.md)

## Training:
* ### Getting started
  * [ ] [The Illustrated Children's Guide to Kubernetes](https://www.youtube.com/watch?v=4ht22ReBjno)
* ### Official Documentation
  * [ ] [Kubernetes](https://kubernetes.io/docs/home/)
  * [ ] [Azure Kubernetes Service (AKS)](https://docs.microsoft.com/en-us/azure/aks/)
  * [ ] [Azure Dev Spaces (AZDS)](https://docs.microsoft.com/en-us/azure/dev-spaces/)
* ### Pluralsight Kubernetes (included) 30h
  * [ ] [Docker and Kubernetes: The Big Picture](https://app.pluralsight.com/library/courses/docker-kubernetes-big-picture/table-of-contents)
  * [ ] [Azure Kubernetes Service (AKS) – The Big Picture](https://app.pluralsight.com/library/courses/azure-container-service-big-picture/table-of-contents)
  * [ ] [Getting Started with Docker](https://app.pluralsight.com/library/courses/docker-getting-started/table-of-contents)
  * [ ] [Getting Started with Kubernetes](https://app.pluralsight.com/library/courses/getting-started-kubernetes/table-of-contents)
  * [ ] [Kubernetes Installation and Configuration Fundamentals](https://app.pluralsight.com/library/courses/kubernetes-installation-configuration-fundamentals/table-of-contents)
  * [ ] [Managing Ingress Traffic Patterns for Kubernetes Services](https://app.pluralsight.com/library/courses/managing-ingress-traffic-patterns-kubernetes-services/table-of-contents)
  * [ ] [Managing the Kubernetes API Server and Pods](https://app.pluralsight.com/library/courses/managing-kubernetes-api-server-pods/table-of-contents)
  * [ ] [Microsoft Azure Developer: Deploying and Managing Containers](https://app.pluralsight.com/library/courses/microsoft-azure-containers-deploying-managing/table-of-contents)
  * [ ] [Managing Kubernetes Controllers and Deployments](https://app.pluralsight.com/library/courses/managing-kubernetes-controllers-deployments/table-of-contents)
  * [ ] [Getting Started with Google Kubernetes Engine](https://app.pluralsight.com/library/courses/getting-started-google-kubernetes-engine/table-of-contents)
  * [ ] [Deploying Containerized Workloads Using Google Cloud Kubernetes Engine](https://app.pluralsight.com/library/courses/google-cloud-kubernetes-engine-deploying-containerized-workloads/table-of-contents)
  * [ ] [Leveraging Advanced Features on the Google Cloud Kubernetes Engine](https://app.pluralsight.com/library/courses/google-cloud-kubernetes-engine-leveraging-advanced-features/table-of-contents)
  * [ ] [Packaging Applications with Helm for Kubernetes](https://app.pluralsight.com/library/courses/packaging-applications-helm-kubernetes/table-of-contents)
* ### Udemy Kubernetes (purchased; training allotment)
  * [ ] [Docker and Kubernetes: The Complete Guide (22h)](https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/)
  * [ ] [Certified Kubernetes Administrator (CKA) with Practice Tests (12h)](https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/)
  * [ ] [Kubernetes Certified Application Developer (CKAD) with Tests (5h)](https://www.udemy.com/course/certified-kubernetes-application-developer/)
  * [ ] [Learn DevOps: The Complete Kubernetes Course (11h)](https://www.udemy.com/course/learn-devops-the-complete-kubernetes-course/)
* ### Cloud Native Computing Foundation
  * [ ] [Introduction to Kubernetes (free)](https://www.cncf.io/certification/training/)
  * [ ] [Kubernetes Fundamentals ($299 USD)](https://www.cncf.io/certification/training/)
  * [ ] [Kubernetes for Developers ($299 USD)](https://www.cncf.io/certification/training/)

## Certification:
* ### Individual:
  * [ ] [Certified Kubernetes Administrator (CKA) Program ($300 USD)](https://www.cncf.io/certification/cka/)
  * [ ] [Certified Kubernetes Application Developer (CKAD) Program ($300 USD)](https://www.cncf.io/certification/ckad/)
* ### Corporate:
  * [ ] [Kubernetes Certified Service Provider](https://www.cncf.io/certification/kcsp/)

## Conference:
* [KubeCon / CloudNativeCon 2020 or 2021](https://events.linuxfoundation.org/events/kubecon-cloudnativecon-north-america-2019/)
  * Registration ($1050 USD)
  * 5 nights @ $200/night ($1000 USD)
  * Flights ($800 CAD)

Each of the exams come with a free retake so I figure I'll go through the pluralsight and udemy courses, try the exams and if I fail then try the Cloud Native Computing Foundation courses.  To get the certifications has the following breakdown:

| Action | Low Cost ($) | High Cost ($) | Cost Videos (hr) | Cost Studying (hr) |
| ------ |-------------:|--------------:|-----------------:|-------------------:|
| CKA cert | 300        | 599           | 80               | 80                 |
| CKAD cert | 300       | 599           | ""               | ""                 |
| Conference | 3000     | 3000          | 40               |                    |
| Total | 3600          | 4200          | 120              | 80                 |

The total cost for exams and certification are $600 - $1200 and approximately 160 hours.
The total cost for the conference would be roughly $3000 and last 1 week.

Overall, I think this email provides a template how a developer would go through learning Kubernetes.  Further, Solvera could pursue the Kubernetes Certified Service Provider if 3 developers are able to achieve the CKA certification.

[1] - Kubernetes provides an abstraction over infrastructure (servers) and applications (containers).  Together these would allow a company to take a monolithic app, 'lift and shift' it to the cloud, and add/rewrite functionality piecemeal in modern technologies.  In the coming years moving monolithic apps to container orchestration systems so greenfield and maintenance work can coexist on hybrid cloud solutions without requiring a total redevelopment of the systems.
