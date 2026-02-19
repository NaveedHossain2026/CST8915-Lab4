# CST8915 Lab 4

**Student Name**: Naveed Hossain
**Student ID**: 0410818822 
**Course**: CST8915 Full-stack Cloud-native Development
**Semester**: Winter 2026

---

## Demo Video

🎥 [Watch Demo Video](https://youtu.be/7yCxoA5OxY8)

---

## Reflection Questions

### What are the main differences between a Docker image and a Docker container?

Docker image is a template or blueprint used to create a container. This container image contains all the libraries, dependencies, and files that the container needs to run. A Docker container is a runtime environment that includes code, runtime, system tools, libraries, and settings needed to run the application code without using host machine dependencies. 


### Explain how Docker's layered architecture improves efficiency.

Docker’s layered architecture improves efficiency by splitting an image into separate layers. When something changes in the code, Docker only rebuilds the layers that changed instead of rebuilding the entire image. This saves time during builds and reduces the use of resources. It also saves storage space because different images can share the same layers, so components like the operating system or runtime don’t need to be stored multiple times.

### Why does each container get its own writable layer?

Each container gets its own writable layer so changes can be made without affecting the original image or other containers. The image is read-only, while the writable layer allows the container to store new or updated data. 

### What are the benefits of using Docker Compose over running containers individually?

The benefits of using Docker Compose is that it allows developers to run and manage multiple containers together as a single unit instead of running them one by one. Services can be defined as a single file and can be started with a single command. It ensures everything is configured consistently, reduces setup errors, and makes development and testing simpler.

---

## Challenges and Learnings 

Because of high latency and frequent disconnections in VS Code on the B2s VM, all tasks and the demo were completed using the terminal.

---

## Acknowledgments

I used Gemini to troubleshoot errors and resolve technical blockers during the lab.
