# Kinesis Data Stream CloudWatch
A demo that will intially deploy a Kinesis data stream with 4 shards and sample python scripts run in Cloud9 that purposly send a higher volume of messages to a single shard on Kinesis. This sets up a scenario with where a Kinesis data stream has a *hot* shard. Subseqently you enable enhanced monitoring on the Kinesis data stream and deploy a CloudWatch dashboard to identify the *hot* shard

## Instructions

1. Deploy CloudFormation for Kinesis + Cloud9

[![Launch CloudFormation Stack](https://sharkech-public.s3.amazonaws.com/misc-public/cloudformation-launch-stack.png)]()

The CloudFormation will deploy the following architecture

<img width="700" alt="OpenSearch_demo_VPC_Architecture" src="https://github.com/ev2900/Kinesis_Data_Stream_Hot_Shard_Demo/blob/main/Architecture/architecture-diagram.png">

2. Enable enhanced shard-level metrics on the Kinesis data stream

*Instructions*
