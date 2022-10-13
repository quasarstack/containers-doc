# Course Directory Structure
Guide to structure directories and files:

#### Imp points:
* Do not use `space` in files and directories name.

**1. `README.md` in top level directory, contains:**
		- Explain couse outline and offering
		- Course content list:
```
# Containers and Orchestration

## Content
1. [Course Introduction](content/1-Course-Information/README.md)
2. [Cloud Native Architecture](content/2-Cloud-Native-Architecture/README.md)
3. [Container Orchestration](content/3-Container-Orchestration/README.md)
4. [Kubernetes Fundamentals](content/4-Kubernetes-Fundamentals/README.md)
5. [Working with Kubernetes](content/5-Working-with-Kubernetes/README.md)
```

**2. In content, each title must be pointed to directrory matching chapter name top level  `content` directory**

| Directory   | Chapters                           |
| ----------- | ---------------------------------  |
| content     | 1-Course-Information               |
| content     | 2-Cloud-Native-Architecture        |

* Chapters directories must be in same order as `README.md`
* Chapters directories name must with start a number(as per the sequence) and use `-` as in above table

**3. Each chapter will have a `README.md` contains topics index covered in chapter**

```
02 CLOUD NATIVE ARCHITECTURE

Index

1. [Introduction](2_1.md)
2. [Cloud Native Architecture Fundamentals](2_2.md)
3. [Characteristics of Cloud Native Architecture](2_3.md)
```
* Each topic listed in index, would have a separate file.
* File name must be as:
```
chapterindex_topicindex.md
```

* Inside each chapter `images` directory will store all images needs to used in chapter
* Image name must be structured as:
```
chapterindex_topicindex-01
```

If the topic has two images, the next image name would be `chapterindex_topicindex-02`