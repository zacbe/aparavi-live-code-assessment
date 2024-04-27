# aparavi-live-code-assessment

Live Code Challenge for Aparavi

## Instructions:

We have a Cloud setup with several servers in which we can create VMs. These VMs need resources like

- CPU power
- Memory
- Disk space.
  Each server can host multiple VMs as long as its capacity is not exceeded. Every VM needs to have all of ist resources on one server.
  Whenever a request for a new VM comes in we need to assign it to a server. The assigned server needs to have the capacity left to incorporate the VM. If no server is capable of hosting the new VM, the application should return and error.
  Write a node.js application which handles the requests, assigns servers to VMs and keeps track of our server capacity. All can be handled in-memory, no database setup needed.
