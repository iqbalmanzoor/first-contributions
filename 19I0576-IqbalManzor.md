Q1) Explain Docker Containers vs VMs:

Docker Containers and Virtual Machines (VMs) are both technologies used for deploying and running applications, but they differ in their architecture and resource utilization:

Architecture:

Docker Containers: Containers are lightweight and share the host OS kernel. They encapsulate an application and its dependencies into a single package, allowing for efficient resource utilization and quick startup times.
VMs: Virtual Machines emulate an entire physical computer, including a complete OS. Each VM runs its own kernel, which makes them bulkier and slower to start compared to containers.
Resource Utilization:

Docker Containers: Containers use fewer resources because they share the host OS kernel and run directly on the host's hardware. This makes them highly efficient in terms of memory and CPU usage.
VMs: VMs require more resources since they run a full OS. Each VM consumes significant memory and CPU, and there is an overhead associated with managing multiple OS instances.
Isolation:

Docker Containers: Containers offer process-level isolation, meaning processes within the same container share the same kernel but have separate filesystems and resources.
VMs: VMs provide stronger isolation as they run separate kernels and complete OS instances, making them more secure but less resource-efficient.
Portability:

Docker Containers: Containers are highly portable because they package an application and its dependencies into a single unit. They can run consistently across different environments.
VMs: VMs are less portable due to their bulkier nature. Moving VMs between different hypervisors or cloud providers can be more challenging.


Q2) docker run -d --name assignment-2-19I0576 -p 9090:80 --network assignment-2 nginx:1.24.0


Q3) ![Docker Screenshot](~/desktop/docker.png)

**Docker Container Logs:**

You can retrieve the container logs using the following command:

```bash
docker logs assignment-2-19I0576
