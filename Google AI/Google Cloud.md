![[Google AI/Screenshot 2025-01-19 at 22.48.50.png]]

The Google Cloud can be divided into three basic layer:
1. **Networking and security** - This is the base for all applications and services in the cloud.
2. **Compute and Storage** - They are decoupled from the underlying layer so that "compute" and "storage" can be scaled on individual needs.
3. **Data and AI products** - The top most layer contains ML model, AI applications to process and store data to process and provide business insights.

## Google's Computing services
1. **Compute Engine** - Provides IaaS offering like Compute, Storage, Network virtually that is similar to a physical machine. Provides maximum flexibility for management of resources.
2. **Google Kubernetes Engine (GKE)** - Runs containerized applications in cloud environment with all dependencies packaged in the container.
3. **App Engine** -  Provides fully managed PaaS offering that binds application to libraries for infrastructure needs. This allows resource to focus on application logic.
4. **Cloud Run** - Run event driven stateless workloads without worrying about servers. Provides abstraction to infra so focus on writing code.
5. **Cloud Run Functions** - Code execution in response to events, e.g. upon file upload to cloud storage. No software installation required. FaaS

## Where does the processing power come from?
![[Pasted image 20250119231443.png]]
Google developer Tensor Processing Unit (TPU) that are domain specific compute as compared to general purpose hardware like CPU and GPU. This allows higher efficiency to meet the needs of computation needs in the domain.

## Storage
![[Screenshot 2025-01-19 at 23.18.48.png]]
Compute and Storage are decouple in Could env as opposed to Desktop env.
Compute and Storage can scale separately.
Google Cloud several storage services:
1. Cloud Storage
2. Bigtable
3. Cloud SQL
4. Spanner
5. Fire Store
6. Big Query

### How do you choose from the different storage services?
Once thing could be based on the type of data (Structured and Unstructured)
![[Pasted image 20250119232810.png]]
Any non tabular data format is _Unstructured_ Data and is suitable for _Cloud Storage_.
There are 4 types of data storage:
![[Pasted image 20250119233023.png]]

_Structured_ data is data stored in Tables -> Columns and Rows
![[Pasted image 20250119233259.png]]

Structured data comes in 2 types (Transactional and Analytical Workloads)
![[Pasted image 20250119233445.png]]