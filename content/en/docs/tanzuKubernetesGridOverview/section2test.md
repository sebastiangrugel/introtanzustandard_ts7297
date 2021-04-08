---
title: "Section 2 Test"
date: 2020-10-09T03:15:26-07:00
weight: 3190
---

All Modernapps Ninja learning content is publicly accessible and available openly, however a free membership is required to take tests and recieve a certificate of completion for the course. You must first [join the community](https://modernapps.ninja/about/membership/) and register for this course per the instructions in the course introduction section before attempting to submit a test.

Ninja tests use devops tools and processes so the testing system itself provides both experience with and validation of foundational devops skills. 

- [Instructions](#instructions)
  - [Full Test Instructions](#full-test-instructions)
  - [Test Answer Response Sheet](#test-answer-response-sheet)
  - [Section 2 Test Questions](#section-2-test-questions)
      - [This concludes the section 2 test. Please use the navigation bar to proceed to the next page.](#this-concludes-the-section-2-test-please-use-the-navigation-bar-to-proceed-to-the-next-page)

{{< youtube J_nV5YPypqs >}}

## Instructions

This test uses automated grading, you must follow the instructions exactly to ensure automated grading will complete successfully. 

To complete the test you must review the questions on this page, and fill in your answers on a seperate answer sheet provided below. We recommend opening the answer sheet for the test in a seperate browser tab so you can fill in the answers as you proceed through the questions. 

Every question in this test is titled "Question" followed by its order, for example Question1, Question2 etc...

All questions will provide a list of possible answers. Each possible answer is represented by a lowercase letter, the first response is option "a", the second is option "b" and so on, as shown in the example questions below. 

The Answer sheet will open in Github's web-based editor, similar to the image shown below:

![Example Test Response Sheet](/introtanzustandard_ts7297/admin/assets/images/blank_test_screen_example.png)  

After you fill in your answer sheet, you will submit  your responses as a git [pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) following the instructions provided below, which will trigger a workflow that will grade your responses and provide your test grading sheet. 

### Full Test Instructions

If this is the first test you have taken, or if you have an questions at all about how to propely complete the test answer sheet or the test grading service, please review the full [How to Take a Test Instructions](https://modernapps.ninja/course_repo_template_ct8279/docs/reference/testinstructions/).  

It is important that you follow the instructions carefully to ensure the automated grading process completes successfully.

### Test Answer Response Sheet

Please right click the following link to the test answer response sheet and select to open it in a new tab. The questions for this test will be provided below in this page, but you will need to enter your responses in the answer response sheet. 

[test2 Answer Response Sheet](https://github.com/modernappsninja/introtanzustandard_ts7297/edit/main/static/admin/userdata/tests/test2.yml)  

### Section 2 Test Questions

#### **Question1:** In Kubernetes what is the name of the node type that runs container workloads? <!-- omit in toc -->

**Please select the best response:**

```yml
Answers:
  a: Master
  b: Server
  c: Worker
  d: Supervisor
  e: Employee
```

#### **Question2:** The Kubernetes object type used to define a container is?  <!-- omit in toc -->

**Please select the best response:**

```yml
Answers:
  a: Image
  b: Target
  c: Pod
  d: ReplicaSet
```

#### **Question3:** When you deploy Kubernetes on vSphere using the vSphere CPI, what vSphere object type is used to provide Persistent Volumes to Kubernetes workloads? <!-- omit in toc -->

**Please select the best response:**

```yml
Answers:
  a: OVA
  b: Datastore
  c: Software-Defined Storage
  d: iSCSI Target
```

#### **Question4:** Which of the following services is included in a generally available open source Kubernetes distribution? <!-- omit in toc -->

**Please select the best response:**

```yml
Answers:
  a: a supported ingress controller
  b: East/West or Pod-to-Pod Load Balancing
  c: Automated deployment of Kubernetes clusters on-demand
  d: North/South or Inbound/Outbound Load Balancing
```

#### **Question5:** Which of the following is NOT a feature of Tanzu Kubernetes Grid <!-- omit in toc -->

**Please select the best response:**

```yml
Answers:
  a: Integrated Logging Agents and Exporter
  b: Multi-Cloud Cluster Management
  c: Offline Installation
  d: Cluster Lifecycle Management
```

#### **Question6:** TKG installation is supported on which of the following infrastructure platforms? (Select 4) <!-- omit in toc -->

**Please select the best 4 options:**

```yml
Answers:
  a: vSphere
  b: OpenStack
  c: Amazon Web Services EC2
  d: VMware Cloud on AWS
  e: Microsoft Windows Server 2012 R2
  f: Red Hat Enterprise Virtualization
  g: Microsoft Azure
```

#### **Question7:** Which of the following are features and benefits of Tanzu Kubernetes Grid (Select 3) <!-- omit in toc -->

**Please select the best 3 responses:**

```yml
Answers:
  a: Automated multicluster operations
  b: Apply access, networking, and container registry policy consistently to a fleet of clusters
  c: Extends the same consistent Kubernetes runtime across your public cloud and edge environments
  d: A continuously maintained catalog of open-source components and applications
  e: Includes local and in-cluster platform services including logging, monitoring, networking, and storage services
  f: Monitor full-stack applications to cloud infrastructures with metrics, traces, span logs, and analytics
```

#### **Question8:** Which of the following services are packaged with Tanzu Kubernetes Grid (Select 3) <!-- omit in toc -->

**Please select the best 3 responses:**

```yml
Answers:
  a: Container Registry Service (Harbor)
  b: Global Site Load-Balancing Service
  c: Logging Services
  d: Authentication Services
  e: Distributed Tracing Service
```

#### **Question9:** True or False: Tanzu Kubernetes Grid Management Cluster can attach and manage externally created kubernetes clusters? <!-- omit in toc -->

**Please select "a" for true, or select "b" for false:**

```yml
Answers:
  a: true
  b: false
```

#### **Question10:** Please select the most correct statement from the options below <!-- omit in toc -->

**Please select the best response:**

```yml
Answers:
  a: TKG uses a Workload Cluster to automate the deployment of Management Clusters
  b: TKG Uses a Management Cluster to automate the deployment of Workload Clusters
```

#### **Question11:** Which of the following attributes can be defined in a Cluster Plan? (Select 2) <!-- omit in toc -->

**Please select the best 2 responses:**

```yml
Answers:
  a: Node Machine Size
  b: Stateful Set
  c: Hypervisor Type
  d: Quantity of Master/Control Plane Nodes
```

#### **Question12:** True or False: All TKG Editions Deploy the same Kubernetes Binaries on Workload Clusters? <!-- omit in toc -->

**Please select "a" for true, or select "b" for false:**

```yml
Answers:
  a: true
  b: false
```

#### **Question13:** Which of the following components are included with Tanzu Kubernetes Grid? <!-- omit in toc -->

**Please select the best 3 responses:**

```yml
Answers:
  a: Integrated Developer Environment
  b: Container Runtime
  c: OVA or Cloud Provider Images for Installation on Supported IaaS Environments
  d: Supported Kubernetes CNI Conformant Networking Options
  e: SaaS Based Management Portal
```

#### **Question14:** Tanzu Kubernetes Grid uses the _____ Kubernetes Project automate the creation of kubernetes clusters  <!-- omit in toc -->

**Please select the best response to fill in the blank word:**

```yml
Answers:
  a: kubespray
  b: BOSH
  c: Cluster API
  d: vRealize Automation

```

#### **Question15:** Tanzu Kubernetes Grid uses the _____ Open Source Software for Data Protection to backup and restore Kubernetes objects <!-- omit in toc -->

**Please select the best response to fill in the blank word:**

```yml
Answers:
  a: Sonobuoy
  b: Velero
  c: Contour
```

#### **Question16:** _________ ______ is a Kubernetes project to bring declarative, Kubernetes-style APIs to cluster creation, configuration, and management. <!-- omit in toc -->

**Please select the best response to fill in the blank words:**

```yml
Answers:
  a: CloudFoundry BOSH
  b: Cluster API
  c: Project Pacific
  d: Cloud Config
```

##### This concludes the section 2 test. Please use the navigation bar to proceed to the next page.
