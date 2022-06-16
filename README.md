# Kinesis Data Stream CloudWatch
A demo that will intially deploy a Kinesis data stream with 4 shards and sample python scripts run in Cloud9 that purposly send a higher volume of messages to a single shard on Kinesis. This sets up a scenario with where a Kinesis data stream has a *hot* shard. Subseqently you enable enhanced monitoring on the Kinesis data stream and deploy a CloudWatch dashboard to identify the *hot* shard

## Instructions

1. Deploy CloudFormation for Kinesis + Cloud9

[![Launch CloudFormation Stack](https://sharkech-public.s3.amazonaws.com/misc-public/cloudformation-launch-stack.png)]()

The CloudFormation will deploy the following architecture

*Architecture*

2. Enable enhanced shard-level metrics on the Kinesis data stream

*Instructions*
