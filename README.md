[![CircleCI](https://dl.circleci.com/status-badge/img/gh/nguyenhoangthienchi/capstone/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/nguyenhoangthienchi/capstone/tree/master)

ChiNHT2 Udacity Cloud Devops Engineer Capstone Project:
- All the screenshots are provided on the folder `result`
- Describe process of CloudFormation stacks creation, order is really import, you can create stack through the AWS Console or use AWS Cli on your choice:
  1. Create stack as below:
      1. Create a network stack with `network.yml`
      2. Create a network stack with `cluster.yml`
      3. Create a network stack with `nodegroup.yml`
  2. The stack name is not important, but you need to update the cluster name to the CircleCI's config file `cluster-name`.
- Result URL:

1. Github repo: https://github.com/nguyenhoangthienchi/capstone

2. Dockerhub: https://hub.docker.com/repository/docker/jayesd3v/capstone/general

3. CircleCI project: https://app.circleci.com/pipelines/github/nguyenhoangthienchi/capstone

4. ELB URL: http://a3e540ec43029480dbf237ebaa7a1bee-1235878639.us-east-1.elb.amazonaws.com/
