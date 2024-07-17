### Questions

Suppose the data is produced by different upstream services, which publish messages to an event broker. Management would like you to design a system to enable all employees within the company to use the data for insights and dashboards. Please make reasonable assumptions if necessary.

1. Which data stack architecture would you choose? Please design an architecture diagram that you present to us in detail in the technical interview.
1. How would you approach this scale in the long term, what are the benefits?
1. What technical and organizational challenges might you need to overcome during the
   implementation of the project?

### Answer

1. Design

   ![Data Architecture Design](data_architecture.png "Data Architecture Design")

1. Benefits

- This could create generic and standard to land data to Data Lake
- Generic and standard can be scaled and automated
- Can convert Metric Layer to data mesh, and shift to data as a service

1. Challenges

- Require much effort to implementation Kafka, Monitoring
- Could increase the cost of storage and processing
- Manage and orchestration could be decentralized to dags, dbt, and monitoring for kafka. But at moment we do not have a tool can do everything.
- Reqire more technical skills
