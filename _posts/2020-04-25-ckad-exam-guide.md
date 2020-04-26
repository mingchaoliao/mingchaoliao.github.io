---
layout: post
title:  "CKAD Exam Guide"
date:   2020-04-25 22:12:46 -0500
---

# CKAD Email Guide

After preparing for 1 month, I passed the Certified Kubernetes Application Developer (CKAD) exam in October 2019. In this post, I would like to share some resources and tips to help people to pass the exam.

## What is Kubernetes?

According to its [official website](https://kubernetes.io/), "Kubernetes (K8s) is an open-source system for automating deployment, scaling, and management of containerized applications."

## What is CKAD?

According to its [official website](https://www.cncf.io/certification/ckad/), "The Certified Kubernetes Application Developer (CKAD) program has been developed by the Cloud Native Computing Foundation (CNCF), in collaboration with The Linux Foundation, to help expand the Kubernetes ecosystem through standardized training and certification. As one of the highest velocity projects in the history of open source, Kubernetes use is exploding."

## How to Get The CKAD certificate?
To get the certificate, you need to:
 1. create a CNCF account
 1. register the CKAD exam for $300
 1. Pick an available exam time
 1. take the online exam and get a score of 66% or above.

> **Note:** You do have a change to **re-take** the exam **ONE** time within the year if you does not pass in the first time.

The exam is:

 - online
 - 2 hours 
 - 19 questions (most questions contain multiple sub-questions)
 - proctored (yes, someone will actively watch you via webcam)
 - hands-on questions only.
 - command line environment in the web browser
 - "open-book" (only official documentations are allowed. No google search! No StackOverflow!)

You are only allowed to open **ONE** extra tab in the browser (beside of the exam panel) in order to access **Kubernetes official documentations** at:

 - [https://kubernetes.io/docs/](https://kubernetes.io/docs/) and its subdomains
 - [https://github.com/kubernetes/](https://github.com/kubernetes/) and its subdomains
 - [https://kubernetes.io/blog/](https://kubernetes.io/blog/)

> **Tip:** In order to navigate documentations faster during the exam, you are allowed to **bookmark** as many documentation links as you want prior to the exam, although you can only open one extra tab to access the documentation,

## Preparation Material

There are more and more resources coming out on the internet. Here is a list of them I used in the before.

### Training Courses
 
 - [Kubernetes Certified Application Developer (CKAD) with Tests](https://www.udemy.com/course/certified-kubernetes-application-developer/): I highly recommend this course. It covers all topics and tricks that you need for the exam. You do not need any prior Kubernetes knowledge. But you do need basic Docker and Docker-Compose knowledge before start this course. Also, the course includes a free browser based practicing platform. It is similar to the exam environment (in some degrees). It includes corresponding hands-on practice for each sections in the course, along with several mock exams and challenges. Without previous Kubernetes knowledge (but Docker experience for years), by taking this course, I passed the exam within a month. 
 - [Docker and Kubernetes: The Complete Guide](https://www.udemy.com/course/docker-and-kubernetes-the-complete-guide/): This course has contains 4 parts: Docker, Docker-Compose, AWS Elastic Beanstalk, and Kubernetes. It covers more than the course above, but is not specific to the CKAD exam. It is useful if you have no container knowledge at all and want to start from the beginning. The instructor will walk though the entire process to build a real-word simple full-stack application (with front-end, back-end, redis cache, database, load-balancing, etc.) and deploy using all 4 different technics.
 
### Blog Posts
 - [CKAD Exam Guide](https://matthewpalmer.net/kubernetes-app-developer/articles/ckad-exam-guide.html)
 - [CKAD.md](https://gist.github.com/veggiemonk/70d95df77029b3ebe58637d89ef83b6b)
 - [Certified Kubernetes Application Developer (CKAD) Exam Tips](https://medium.com/faun/ckad-exam-tips-6e00cc56b6a1)
 - [How To Pass the Certified Kubernetes Application Developer (CKAD) Exam](https://medium.com/bb-tutorials-and-thoughts/how-to-pass-the-certified-kubernetes-application-developer-ckad-exam-503e9562d022)
 - [Study Guide: Certified Kubernetes Application Developer (CKAD) Exam](https://www.cloudreach.com/en/resources/blog/study-guide-certified-kubernetes-application-developer-ckad-exam/)
 - [Certified Kubernetes Exams: Tips and Tricks to Pass the CKA and CKAD Exam](https://dev.to/kodekloud/tips-and-tricks-to-pass-the-cka-and-ckad-exam-c76)
 - [Certified Kubernetes Application Developer (CKAD) Exam Tips](https://devblogs.microsoft.com/premier-developer/certified-kubernetes-application-developer-ckad-exam-tips/)
 - [https://unofficialism.info/posts/unofficial-tips-for-cka-and-ckad-exams/](https://unofficialism.info/posts/unofficial-tips-for-cka-and-ckad-exams/)

### Exercises

 - [CKAD Exercises](https://github.com/dgkanatsios/CKAD-exercises)
 - [Practice Enough With These 150 Questions for the CKAD Exam](https://medium.com/bb-tutorials-and-thoughts/practice-enough-with-these-questions-for-the-ckad-exam-2f42d1228552)
 - [Practice Exam for Certified Kubernetes Application Developer (CKAD) Certification](https://matthewpalmer.net/kubernetes-app-developer/articles/ckad-practice-exam.html)
 - [Kubernetes CKAD Example Exam Questions Practical Challenge Series](https://codeburst.io/kubernetes-ckad-weekly-challenges-overview-and-tips-7282b36a2681)

## My Exam Experience

My exam experience in October 2019 was like:

20 minutes before the exam:

1. Walk in a empty room with my laptop and a bottle of water (pencil and paper are not allowed).
1. Close all opened applications, except the web browser, Chrome.
1. Run the [compatibility check tool](https://www.examslocal.com/ScheduleExam/Home/CompatibilityCheck) and make sure all items pass, especially webcam and speaker are connected.
1. Close all other tabs in the Chrome, except the exam panel and a tab for documentation

The exam panel (in the web browser tab) has two major parts. Questions are displayed in the left half of the screen and command line console are in the right half of the screen. There is a tool bar on the top that you can:
 - open a notepad (a floating panel in the browser)
 - end the exam
 - etc.

There is also a chat box in the bottom-left corner of the screen that you can use to chat with the proctor.

After the exam begins:

1. The proctor starts to chat with me in the chat box.
1. I was asked to hold a government-issued photo ID on hand in front of the webcam for the proctor to ensure my identity.
1. I was asked to hold the webcam and turn around slowly to check and ensure there is no prohibited items around me.
1. I was asked to open task manager on my laptop to check and ensure there is no running applications, except the web browser.

At anytime during the exam, you can click the "end exam" button in the tool bar to end the exam. Otherwise, the exam will end once the remaining time is over.


## Tips & Tricks

Complete all 19 questions in 2 hours in the exam is not a simple task. After reading many posts from other people, they all mention that lacking time is the major reason of failing the exam. Therefore, time management is important for examinees during the exam. Many strategies are introduced in the below to help examinees to save time in the exam.

### Read Official Resources Carefully

The CNCF provides several resources to help examinees to prepare the exam. Here is a list of items:

 - [CAKD Program Home Page](https://www.cncf.io/certification/ckad/)
 - [Official Curriculum Overview](https://github.com/cncf/curriculum)
 - [Official Candidate Handbook](https://training.linuxfoundation.org/go/cka-ckad-candidate-handbook)
 - [Official Exam Tips](http://training.linuxfoundation.org/go//Important-Tips-CKA-CKAD)
 - [Official Q & A](http://training.linuxfoundation.org/go/cka-ckad-faq)

### Run Compatibility Check Took Beforehand

It is very important to run the [compatibility check tool](https://www.examslocal.com/ScheduleExam/Home/CompatibilityCheck) at list a day before the exam on your exam machine (a desktop/laptop of your choice). You will not be allowed to take the exam on the exam day if your computer does not pass the compatibility test.

Especially, you have to prepare a **webcam** and **speaker** and make sure they are proper connected, as they are required during the exam.

### Bookmark Documentation Links That Matches Kubernetes Version Used In The Exam

You are only allowed to open one extra browser tab during the exam to access the official documentations. You can, however, bookmark links from the documentations.

Before you bookmark any page, check the Kubernetes version used in the exam first from the [Official Q & A](https://www.cncf.io/certification/cka/faq/). For example, if the exam (at the time) uses Kubernetes v1.13. Then, you may bookmark [Kubernetes API Reference Doc v1.13](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.13/), rather than the one for the most current version (e.g. v1.15).

### Ability to Fast Navigate Inside The Kubernetes API Reference Doc

Although you are allowed to access other official Kubernetes documentation (e.g. blog, github pages, etc.) during the exam, I am highly recommended to open only [Kubernetes API Reference Doc v1.13](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.13/) (make sure the version matches the one exam used) at all time, unless you have to check other docs. 

By navigating in the API Reference Doc, you should get enough information for the exam. If you fell that you have to check other docs frequently when doing mock exams, it means you are not proficient in Kubernetes knowledge (in exam level). In that case, you may not have enough time to complete all questions in the exam time.

With a certain proficiency level of Kubernetes knowledge, An example that you may need to access the API Reference Doc during the exam could be:
 
> I want to define a container environment variable with a value from a ConfigMap. I remember the yaml configure all the way to the `env` attribute in the container configuration. But I don't quite remember the field name in the next level, whether it's called `from` or `valueFrom` or something else.

In the case above, the fastest ways to lookup the field name in that level is to navigate in the API Reference Doc:
 1. Navigate to **Pod v1 core** from the panel on the left.
 1. Navigate to **PodSpec**
 1. Navigate to **Container**
 1. Navigate to **EnvVar**
 1. find out that the field name is **valueFrom**

### Command Line Equivalent Of The API Reference Doc

There is a command line tool which is equivalent to the [Kubernetes API Reference Doc](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.13/), `kubectl explain <resource>`.

Consider the example from the previous tip. In order to find the field name in the `env` attribute in the container configuration, it can be achieved by using the command: `kubectl explain pod.spec.containers.env`.

### Command Alias (kubectl)
"kubectl" is not a short command comparing to others, e.g. ls, cmd, etc. In order to save time in the exam, creating an command alias for "kubectl" is recommended.

One possible way is to add a line to the end of `.bashrc` file in the home directory:
```text
...
...

alias k=kubectl
```

> **Note:** Don't forget to apply the configuration by using `source ~/.bashrc`.

You can then use the `k` to replace the full command `kubectl`. For example:

 - `k get pods`
 - `k describe pod my-pod`
 - etc.

### Memorize Command Short Names

"kubectl" sub-commands support many short names arguments and options. For example, `kubectl get namespaces` is equivalent to `kubectl get ns`. Combining with command alias from the previous tip, the command can be as short as `k get ns`. Obliviously, it is much faster to type commands in this way than typing the full command.

You can find a full list of resources types in the short name form on the [Kubectl Overview](https://kubernetes.io/docs/reference/kubectl/overview/#resource-types). Here is a list of short names that are commonly used in the exam:

|Resource Name|Short Names|
|:------------|:----------|
|configmaps|cm|
|namespaces|ns|
|persistentvolumeclaims|pvc|
|persistentvolumes|pv|
|serviceaccounts|sa|
|services|svc|
|deployments|deploy|
|replicasets|rs|
|cronjobs|cj|
|networkpolicies|netpol|

In additional to the resource type short names, there are several other option short form that may be helpful. For example (with alias):

|Full Command|Short Forms|
|------------|-----------|
|k get pods --all-namespaces|k get pods -A|
|k get pods --selector='label1=key1'|k get pods -l label1=key1|
|k get pod my-pod --output='yaml'|k get pod my-pod -o yaml|

### Force Delete Pod Without Waiting

Delete a pod is slow by using command `kubectl delete pod <pod name>`. It may takes up to 10-20 seconds to complete. There is a way to boost the progress that you can use during the exam, `kubectl delete pod my-pod --grace-period=0 --force`. It will instantly complete the command, so that you can continue on issuing other commands, although the pod may not immediately deleted internally.

### Weight of Questions are different
Weight of questions are different. Some simple questions may have a high score weight. In contrast, some tough questions may have a low score weight. In order to maximize scores you can earn in the exam, I suggest that you can skip tough questions with low score weight in the first round and complete all sample questions with high score weight first.

Support there are 5 questions in the exam (although there are actually 19 question in the real exam):

|Question #|Difficulty|Score Weight|
|----------|----------|------------|
|1|Easy|10|
|2|Hard|2|
|3|Median|3|
|4|Easy|8|
|5|Median|5|

The strategy could be:

Round #1:  
 1. Complete #1
 1. Skip #2
 1. Skip #3
 1. Complete #4
 1. Skip #5
 
Round #2:
 1. Complete #5
 1. Complete #3
 
Round #3:
 1. Complete #2
 
Always remember, do not spend too many time  in the first round on questions that:
 - you do not have solution in the mind immediately
 - is too long and have many sub-questions
 - is tough and only has a low score weight

Otherwise, you may not has the chance to complete all questions in the exam, and end up with failing the exam.

### Practice A Lot Is The Key To Success

The CAKD exam is a performance-based, on-hand exam. You do not need to memorize theories, features pros/cons, or other texts when preparing the exam. However, you do need to understand how to create/modify/inspect/monitor/delete objects in all domains required in the exam curriculum. 

You can install [minikube](https://kubernetes.io/docs/tasks/tools/install-minikube/) (a single node Kubernetes cluster for non-production usage) and practice on it. 

Practice! Practice! Practice a lot! Practice to as fast as you can to operate objects, which is the key to success in the exam.

### Be Cautious Of Namespaces, Nodes and Contexts

In the exam, different questions may ask you to operate objects in the different namespaces and nodes. 

First of all, do not worry if you don't know how to switch between nodes and contexts. The question will always provide command for you to switch between them.

However, you still need to be cautious of which namespaces, nodes or Contexts that the question asks you to operate objects in. Otherwise, you will have to re-do it in the right environment (if you find out later), or get 0 score (if you do not realize it).

### Always Export Existing Object into Yaml File

In the exam, you may be asked to modify a specified object (e.g. fix a typo in the image name in a deployment). You have the option to edit and re-apply the deployment by using the command: `kubectl edit <resource name>`.

Be cautious, editing the object directly is risky since you have no way to revert back to its original state, if anything goes wrong. I recommend that always export the existing object to a yaml file, modify it and re-apply it:

1. export to a yaml file: `kubectl get deployment my-deployment -o yaml > my-deployment.yaml`
1. modify the yaml file, my-deployment.yaml
1. re-apply the deployment: `kubectl apply -f my-deployment.yaml`

### Out-Of-Scope Resources/Objects

There are several Kubernetes objects that may not present in the exam. 

> **Warning:** I cannot guarantee that the items listed below will not present in your exam.

 - `ReplicaSet v1 apps`: According to the official documentation, the ReplicaSet is recommended to be replace by the Deployment resource. You (should) not see any question that ask you to create or modify a ReplicaSet.
 - `Ingress v1beta1 Extensions`: Ingress depends on the underling infrastructure, e.g. AWS, GCP, etc. You (should) not be asked to operate ingress in the exam.
 - `PersistentVolume v1 core`: PersistentVolume depends on the underline infrastructure. You (should) not be asked to create a PersistentVolume in the exam. However, you will see questions that ask you to create a **PersistentVolumeClaim** which uses some existing volumes.

### Declarative vs Imperative

In the Kubernetes world, there are 2 ways to operate a object, declarative and imperative. For example, to create a pod using image `busybox`, the imperative way is to run the command `kubectl run my-pod --image busybox`. In contrast, the declarative ways is to create a yaml file, `my-pod.yaml`:
```yaml
apiVersion: v1
kind: Pod
metadata: 
  name: my-pod
spec:
  containers:
    - name: busybox
      image: busybox
```
and apply it, `kubectl apply -f my-pod.yaml`.

In the example above, it seems like that operating a object in the imperative way is faster than using the declarative way. It is not always true, especially once the requirement becomes more complex. The imperative solution does not give much flexibility compared to its counterpart. With complex requirement, users have to create a pod using the imperative command, export it to a yaml file, modify it, delete the old one and finally apply the one needed.

In addition, the imperative solutions does not keep any trace and backup of previous states. There is no way to revert back to the state in the before, and even people may not know what they changed in the before once they lose their command line history. 

In contrast, the declarative solution is more controllable. You can always get what you put in the yaml file. You can also keep a copy of yaml file before you want to change it, so that once the change is not what you want, then you can always re-apply the backup yaml file to revert to the previous state.

I saw in many other posts that they does not recommend using declarative solution in the CKAD exam. My opinion is that it depends. **You use whatever you are comfortable with, imperative or declarative**. In the exam I took in October 2019, I used declarative solutions for all cases and still got all question completed in about 1 hour 20 minutes (then I had another 40 minutes for review). 

### Auto Indent In The Text Editor

In the CKAD exam, examinees have to create and/or edit many yaml files. A valid yaml file requires strict indent in each levels. To save some time of typing tons of spaces/tabs and to avoid unnecessary indent errors, It is highly recommended to setup auto-indent in the text editor.

By default, the exam console provides two text editors, nano and vim (I can't remember whether `emacs` is provided or not). Depend on your own preference, you should memorize the auto-indent configuration prior to the exam and setup the environment as soon as you are allowed to login the exam system.

Here is a example of setup auto-indent in the `nano`. Create or update the file `.bashrc` in the home directory:

```text
set tabsize 2
set tabstospaces
set autoindent
``` 

> **Note**: After modify the `.bashrc` file, don't forget to apply the configuration by using the command `source ~/.bashrc`.

### Command is NOT executed within a shell.

Consider the question below:
> Create a pod using image `busybox`. The busybox container should run the command: `while true; do date; sleep 1;done`.

A wrong solution:
```yaml
apiVersion: v1
kind: Pod
metadata:
  name: tip1-pod
spec:
  containers:
    - name: busybox
      image: busybox
      command: ["while true; do date; sleep 1;done"]

```
Once the pod is deployed, inspect the pod, `kubectl describe pod tip1-pod`.
```text
...
...

Events:
  Type     Reason     Age                From               Message
  ----     ------     ----               ----               -------
  ...
  ...
  Warning  Failed     9s (x2 over 10s)   kubelet, minikube  Error: failed to start container "busybox": Error response from daemon: OCI runtime create failed: container_linux.go:346: starting container process caused "exec: \"while true; do date; sleep 1;done\": executable file not found in $PATH": unknown

...
...
```

What is wrong?

The `command` (entrypoint) or `args` (command) set in the container will `NOT` be executed within a shell. Therefore, the usual shell functions, like while loop, stdout redirection, etc. won't work!

How to fix it?

Invoke a shell and execute the while loop in it: `sh -c "<command goes here>"`

The correct solution:
```yaml
apiVersion: v1
kind: Pod
metadata:
  name: tip1-pod
spec:
  containers:
    - name: busybox
      image: busybox
      commands: ["sh", "-c"]
      args: ["while true; do date; sleep 1;done"]
```

A little bit more, what if the question ask to write the output from the while look into a file `/tmp/result.txt`?

Everything should be the same as the solution above, except the `args` option:
```text
...
...
args: ["while true; do date; sleep 1;done > /tmp/result.txt"]
...
...
```

### How to Set a Multi-line Value in the ConfigMap?

It is actually not a Kubernetes specific trick. It is related to the knowledge of how to set a multi-line value in a Yaml file.

Consider the question below:
> Create a `ConfigMap` with a key `NGINX_CONFIG` and value:
> ```text
> server {
>   listen 80;
> }
> ```

The key point of using a multi-line string as value is to add a pipe (`|`), and then follow by the multi-line string in the next line (with indent):
```yaml
apiVersion: v1
kind: ConfigMap
metadata:
  name: tip2-configmap
data:
  NGINX_CONFIG: |
    server {
      listen 80;
    }
```
