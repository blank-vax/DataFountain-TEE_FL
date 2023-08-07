# Architecture Description For Data Provider B

## cert2

This folder stores the certificates used for SSL communication. These certificates are issued and distributed by the CA according to the domain names of the participants before the initialization of this system.

## protos

Sample code for Proto serialization files.

##clientB

System intermediate results and final operating results.

* datahashA.txt: the hash of the data provided by task initiator A stored for subsequent verification;
* idlist.txt: the negotiated idlist of negotiated data in order to ensure the consistency of the forecast data;

## dataset_preprocess.py

Data preprocessing.

## greeter_machineB.py

Related operations of data provider B in RPC interaction.

## helloworld_pb2\*.\*

gRPC communication related documents. `helloworld_pb2.py` and `helloworld_pb2_grpc.py` are generated by `python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. ./helloworld.proto`

## Data

train_b.txt & test_b.txt;

链接: https://pan.baidu.com/s/1QljKHtngQWNxj7NZOzeQzg 提取码: zbhd