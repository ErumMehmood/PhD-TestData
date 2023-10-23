# PhD-TestData
Test data: To analyze the performance of Integrated Real-Time Distributed Stream-Disk Processing Architecture for Un-structured Big Data
https://archive.org/details/stackexchange

Datasets used for Experiments
The details of datasets stored on the local machine used for the evaluation of both architectures are described.

Architecture-1:
To supplement the validation process and support the claim, real-world datasets meta products, meta kindle store and Users.XML are used which
are obtained from cs.meta.stackexchange in the form of XML file to conduct experiments. For the local system, eight datasets with varying numbers of documents/tuples for the meta products
and Users- are created in order to make them big enough to fit on 0.5GB, 1GB, 2GB, and 4GB criteria. Dataset1-4 have been used during the result analysis of architecture-1 while datasets named Users1-4 have been used for the evaluation of architecture-2. Initially, real-life dataset selected was of 700MBs Users.XML in the form of XML file. Downloaded dataset’s XML format has to be converted into CSV in order to import it into MongoDB, which will act as the distributed data store layer.

Architecture-2:
A case study is outlined in this subsection where the DHSGJArch was put to the test. Data has been downloaded from cs.meta.stackexchange for this case study in the form of XML files. Users.XML file: converted and imported into MongoDB, is used as stored dataset and Comments.XML file is adopted for stream generator. At-least one common attribute: UserId, is contained
by both of these files. Three formats have been adopted as an initial step in the production of message streams on Kafka topics: JSON, XML and Raw data.
The Comments.XML file is transformed into raw data and JSON formats to assess DHSGJArch’s performance and investigate how heterogeneous data streams are consumed.
