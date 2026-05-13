# Common DevOps Questions

<h3>Kubernetes Questions</h3>
- What is helm and how do you use it. 
- What is Requests and Memory in Pod. How do they work and the common errors (OOMkilled, CPU throttling)
- What is PDB's and why do we need it.
- What would u do if had no PDB's in prod, would that cause a downtime?
- Have you worked on istio, do you know what service mesh is?
- Why would you use Istio? We use istio becaue it provides encryption, circuit breaking, canary stuff and a lot features out-of-the-box. If we want to encrypt communication between two pods we can sinply inject envoy side-car contianer in our worload pod and the communication will get encrypted. 
- We can setup gateways, virtual services, destination rules using Isito. 

<h3>DevOps Questions</h3>
- What do you know about SRE frameworks SLA etc.

<h3>Cloud Questions</h3>
- What would you do if you had production setup in one AWS region, and the entire region gets down. What would you do get prod back. It's gonna cause downtime. There are many strategies and answers to this question. 
