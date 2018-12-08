# **Big Data Processing**

The prject aims to store and process large airline transportation dataset to answer different types of queries. we will process in batch processing modes (using Hadoop/Cassandra, and separately using Spark) and stream processing mode (using Storm).

The project was based on University of Illinois at Urbana-Champaign' [Cloud Computing Specialization](https://www.coursera.org/specializations/cloud-computing) Capstone Project.


---
Project Specification
---

The project will use a [transportation dataset](https://aws.amazon.com/datasets/transportation-databases/) from the US Bureau of Transportation Statistics (BTS) that is hosted as an Amazon EBS volume snapshot.

The dataset used in the Project contains data and statistics from the US Department of Transportation on aviation, maritime, highway, transit, rail, pipeline, bike/pedestrian, and other modes of transportation in CSV format. The data is described in more detail by the [Bureau of Transportation Statistics](https://www.transtats.bts.gov/DataIndex.asp). (Note that the dataset we are using does not extend beyond 2008, although more recent data is available from the previous link.) In this Project, we will concentrate exclusively on the aviation portion of the dataset, which contains flight data such as departure and arrival delays, flight times, etc. For an example of analysis using this dataset, see Which flight will get you there fastest?

We will process database with both batch processing systems (Apache Hadoop and Spark), and in a stream processing system (Apache Storm). 

The set of questions that must be answered using this dataset is provided in the next section. These questions involve discovering useful information such as the best day of week to fly to minimize delays, the most popular airports, the most on-time airlines, etc. Each task will require you to answer a subset of these questions using a particular set of distributed systems. The exact methodology used to answer the questions is largely left to you, but you must integrate and utilize the specified systems to arrive at your answers.

Questions


---
Contribution
---

Contributions are welcome! For bug reports or requests please submit an [issue](https://github.com/tranlyvu/big-data-processing/issues).

For new feature contribution, please follow the following instruction:

```
1. Fork the repo (https://github.com/tranlyvu/big-data-processing.git)
2. Create your feature branch (`git checkout -b new/your-feature`)
3. Commit your changes (`git commit -am 'Add some new feature'`)
4. Push to the branch (`git push origin new/your-feature`)
5. Create a new Pull Request at https://github.com/tranlyvu/big-data-processing/pulls
```

---
Contact
---

Feel free to contact me to discuss any issues, questions, or comments.
*  Email: vutransingapore@gmail.com
*  Linkedln: [@vutransingapore](https://www.linkedin.com/in/tranlyvu/)
*  GitHub: [Tran Ly Vu](https://github.com/tranlyvu)

---
License
---

See the [LICENSE](https://github.com/tranlyvu/big-data-processing/blob/master/LICENSE) file for license rights and limitations (Apache License 2.0).