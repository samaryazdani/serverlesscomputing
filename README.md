# serverlesscomputing

- Groundhog: Efficient Request Isolation in FaaS

Mohamed Alzayat, Jonathan Mace, Peter Druschel, Deepak Garg
https://arxiv.org/abs/2205.11458

- Object as a Service (OaaS): Enabling Object Abstraction in Serverless Clouds

Pawissanutt Lertpongrujikorn, Mohsen Amini Salehi
https://arxiv.org/abs/2206.05361

- Transparent Serverless execution of Python multiprocessing applications

Aitor Arjona, Gerard Finol, Pedro Garcia-Lopez
https://arxiv.org/abs/2205.08818

- Cloud programming simplified: A berkeley view on serverless computing

Eric Jonas et al.
https://arxiv.org/abs/1902.03383

- Serverless computing: Behind the scenes of major platforms

Daniel Kelly, Frank Glavin, Enda Barrett
https://ieeexplore.ieee.org/abstract/document/9284261/

- Serverless computing: One step forward, two steps back

Joseph M Hellerstein, Jose Faleiro et al.
https://arxiv.org/abs/1812.03651


- The server is dead, long live the server: Rise of Serverless Computing, Overview of Current State and Future Trends in Research and Industry

Paul Castro, Vatche Ishakian, Vinod Muthusamy, Aleksander Slominski
https://arxiv.org/abs/1906.02888

- A review of serverless use cases and their characteristics

Simon Eismann, Joel Scheuner et al.
https://arxiv.org/abs/2008.11110

- Booting 10K Serverless Functions within One Second via RDMA-based Remote Fork

Xingda Wei, Tianxia Wang, Jinyu Gu, Yuhan Yang, Fangming Lu, Rong Chen, Haibo Chen
https://arxiv.org/abs/2203.10225

- Faa $ T: A transparent auto-scaling cache for serverless applications

Francisco Romero et al.
https://dl.acm.org/doi/abs/10.1145/3472883.3486974


SOSP

Faster and Cheaper Serverless Computing on Harvested Resources
Yanqi Zhang, Ingio Goiri, Gohar Irfan Chaudhry

Their solution is based on the exploration of hosting on Harvest VMs of Microsoft Azure
They have modified OpenWhisk to achieve their goals. 


Bladerunner: Stream Processing at Scale for a Live View of Backend Data Mutations at the Edge
Jeff Barber, Ximing Yu, Laney Kuenzel Zamore

The essence is a set of bank-end stream processors that obtain streams of social graph updates and process them on a per application and per-user bases before pushing selected updates to user devices. Separate stream processors are used for each application to enable application-specific customisation, complex filtering, aggregation and other message delivery operations on a per-user basis. 

Boki: Stateful Serverless Computing with Shared Logs

The key enabler is the metal, a novel mechanism that allows Boki to address ordering, consistency and fault tolerance independently. 


ASPLOS 22

IceBreaker: warming serverless functions better with heterogeneity 
Rohan Basu Roy, Thirthak Patel
Cold Start problem

Their real-system evaluation confirm that IceBreaker reduces the overall keep-alive cost by 45% and execution time by 27% using representative serverless applications and industry-grade workload trace. 

INFloss: a native serverless system for the low-latency high throughput inference
Yann Yang, Laiping Zhao
Based on ML
They argue that patching general serverless systems does not resolve the problem completely, we propose that such a system should natively combine the features of inference with a serverless paradigm. INFless, provides a unified, heterogeneous resource abstraction between CPU and accelerators, and achieves high throughput using build-in batching and non-uniform scaling mechanisms. 

FaasFlow: enable efficient workflow execution for function-as-a service
Zijun Li, Yushi Liu
They argue that traditional master-worker based workflow execution architecture performs poorly in serverless context. To this end, they present a worker-side workflow schedule for serverless workflow execution. 


Serverless computing on heterogeneous computers
Dong Du, Qingyuan Liu
They rely on heterogeneous computing. To achieve these results we first propose XPU Shim, a distributed shim to bridge the gap between underlying multi-OS systems (when using general-purpose devices) and the serverless runtime (i.e. Molecule)




CoolEdge: hotspot-relievable warm water cooling for efficient edge datacenter
Qiangyu Pei, Shutong Chen

Based on Edge Computing

The requirements of proximity to end-users, high density, and heterogeneity, present new challenges to cool the edge datacenter efficiently. Although the warm water cooling has become a promising cooling technique for this infrastructure, the one-size-fits all rolling control would lower the cooling efficiency considerably because of the severe thermal imbalance across servers, hardware and even inside one hardware component in an edge datacenter. 


ASPLOS 21
Benchmarking, analysis, and optimisation of serverless function snapshots
Dmitri Usiugov, Plamen Petrov, Marios Kogias, Edouard Bugnion
Cold Start Problem
This work introduces vHive , an open source framework for serverless experimentation with the goal of enabling researchers to study and innovate across the entire serverless stack. Using vHive, the researchers characterise a state-of-the art snapshot based serverelss infrastructure, based on industry-leading Containered orchestration framework and firecracker hypervisor technologies. 


