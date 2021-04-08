---
title: "Section 4 Test"
date: 2020-10-09T03:15:26-07:00
weight: 5190
---

All Modernapps Ninja learning content is publicly accessible and available openly, however a free membership is required to take tests and recieve a certificate of completion for the course. You must first [join the community](https://modernapps.ninja/about/membership/) and register for this course per the instructions in the course introduction section before attempting to submit a test.

Ninja tests use devops tools and processes so the testing system itself provides both experience with and validation of foundational devops skills. 

- [Instructions](#instructions)
  - [Full Test Instructions](#full-test-instructions)
  - [Test Answer Response Sheet](#test-answer-response-sheet)
  - [Section 4 Test Questions](#section-4-test-questions)
      - [This concludes the section 4 test. Please use the navigation bar to proceed to the next page.](#this-concludes-the-section-4-test-please-use-the-navigation-bar-to-proceed-to-the-next-page)

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

[test4 Answer Response Sheet](https://github.com/modernappsninja/introtanzustandard_ts7297/edit/main/static/admin/userdata/tests/test4.yml)  

### Section 4 Test Questions

#### **Question1:** Please select the statements below that describe Tanzu Mission Control capabilities <!-- omit in toc -->

**Please select the best response:**

```yml
Answers:
  a: Provides a centralized management platform for consistently operating and securing your Kubernetes infrastructure and modern applications across multiple teams and clouds.
  b: Is a a ubiquitous kubernetes image that works across all clouds
  c: Is a next-generation cloud firewall
  d: Provides complete modern software development supply chain including build and CI/CD services
```

#### **Question2:** Which of the following are key capabilities of Tanzu Mission Control?  <!-- omit in toc -->

**Please select the best response (Select 1):**

```yml
Answers:
  a: Cluster lifecycle management
  b: Attaching clusters
  c: Centralized policy management
  d: Observability and diagnostics
  e: Identity and access management
  f: Cluster inspection
  g: All of the above
```

#### **Question3:** Which of the following are benefits of Tanzu Mission Control (Select 3) <!-- omit in toc -->

**Select the best 3 responses:**

```yml
Answers:
  a: Converts your Kubernetes Clusters to ClusterAPI Mode
  b: Increases developer agility and productivity
  c: Enhances operational efficiency
  d: Comprehensive CI/CD Pipeline Automation
  e: Strengthens security and compliance
```

#### **Question4:** True or False: Tanzu Mission Control can be used to provision new kubernetes clusters?  <!-- omit in toc -->

**Select "a" for true, or "b" for false:**

```yml
Answers:
  a: true
  b: false
```

#### **Question5:** Which of the following is NOT part of the Tanzu Mission Control architecture? <!-- omit in toc -->

**Select the best response:**

```yml
Answers:
  a: Resource Hierarchy
  b: Build Service
  c: Policy Framework
  d: Health Monitoring
```

#### **Question6:** Which of the following items are part of the Tanzu Mission Control Policy Framework Layer (Select 3): <!-- omit in toc -->

**Select the best 3 responses:**

```yml
Answers:
  a: Identity and Access Management
  b: Namespaces
  c: Wavefront
  d: Audit and Compliance
  e: Data Protection
  f: Managed Clusters
```

#### **Question7:** What is the name of the open source component that Tanzu Mission Control uses to create Kubernetes clusters? <!-- omit in toc -->

**Select the best response (Select 1):**

```yml
Answers:
  a: KOPS
  b: ClusterRPC
  c: CloudFoundry Container Runtime
  d: ClusterAPI
  e: BOSH
```

#### **Question8:** Tanzu Mission Control can manage attached kubernetes clusters hosted on which of the following IaaS Platforms? <!-- omit in toc -->

**Select the best response: (Select 1)**

```yml
Answers:
  a: GCE/GKE
  b: Azure
  c: vSphere
  d: AWS
  e: TKG
  f: TKGI
  g: All of the above
```

#### **Question9:** True or False: Attached Clusters can leverage all of the same TMC features as a cluster created by TMC? <!-- omit in toc -->

**Select "a" for true, or "b" for false:**

```yml
Answers:
  a: true
  b: false
```

#### **Question10:** True or False: A dedicated VPN connection from the customer premise to VMware Cloud is required to attach kubernetes clusters to TMC? <!-- omit in toc -->

**Select "a" for true, or "b" for false:**

```yml
Answers:
  a: true
  b: false
```

#### **Question11:** Please select the statment below that most accurately describes the Tanzu Mission Control resource hierarchy: <!-- omit in toc -->

**Select the best response:**

```yml
Answers:
  a: Organizations and Workspaces are children of Cluster Groups
  b: Workspaces and Cluster Groups are children of Organizations
  c: Cluster Groups and Organizations are children of Workspaces
```

#### **Question12:** Please select the statements below that most accurately describes the Tanzu Mission Control resource hierarchy (Select 2): <!-- omit in toc -->

**Select the best response:**

```yml
Answers:
  a: Workspaces group together multiple clusters and allow policy to be applied uniformly across the Workspace
  b: Cluster Groups group multiple clusters together and allow policy to be applied uniformly across the Cluster Group
  c: Cluster Groups group together multiple namespaces from various clusters and allow policy to be applied uniformly across the Workspace
  d: Workspaces group together multiple namespaces from various clusters and allow policy to be applied uniformly across the Workspace
```

#### **Question13:** True or False: Administrators using Tanzu Mission Control must provide user permissions individually on each cluster a user needs access to: <!-- omit in toc -->

**Select "a" for true, or "b" for false:**

```yml
Answers:
  a: true
  b: false
```

#### **Question14:** True or False: The Tanzu Mission Control Policy Model cascades policies down a hierarchy tree: <!-- omit in toc -->

**Select "a" for true, or "b" for false:**

```yml
Answers:
  a: true
  b: false
```

#### **Question15:** Which of the following are accurate examples of policy inheritence flow in the Tanzu Mission Control policy model (Select 3): <!-- omit in toc -->

**Select the best 3 responses:**

```yml
Answers:
  a: An organization inherits from a cluster group
  b: A workspace inherits from an organization
  c: A policy inherited from an organization overrides a policy directly applied to a cluster group
  d: A cluster group inherits from an organization
  e: A policy directly applied to a workspace overrides a policy inherited from an organization
```

#### **Question16:** What is the name of the open source software that supports the conformance inspection features in Tanzu Mission Control? <!-- omit in toc -->

**Select the best response:**

```yml
Answers:
  a: Prow
  b: Sonobuoy
  c: Helm
  d: Istio
```

#### **Question17:** Select the 2 standard inspection types provided by Tanzu Mission Control: <!-- omit in toc -->

**Select the 2 best options:**

```yml
Answers:
  a: Simple
  b: Extended
  c: Conformance
  d: Lite
  e: Quick
```

##### This concludes the section 4 test. Please use the navigation bar to proceed to the next page.
