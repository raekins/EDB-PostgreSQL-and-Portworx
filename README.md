# EDB PostgreSQL and Portworx Storage
**Kubernetes manifests for EDB Kubernetes PostgreSQL database and Portworx Storage

## Getting Started

1. Create a Kubernetes Cluster using preffered distribution.
1. Follow install instructions from (https://www.enterprisedb.com/docs/kubernetes/cloud_native_postgresql/installation_upgrade/)
1. Pull this Repo
1. Create Portworx Storage Class
1. Create PostgreSQL Cluster

### Portworx Storage Class
`
$ kubectl apply -f px-postgreSQL-sc.yaml.yaml
`
### PostgreSQL Cluster
$ kubectl apply -f px-postgreSQL-cluster.yaml
`

## Authors

Ron Ekins, Principal Solutions Architect, Office of the CTO at Pure Storage

Oracle ACE Director

@ronekins

## License

This module is available to use under the Apache 2.0 license, stipulated as follows:

Copyright 2018 Pure Storage, Inc.
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0 Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on  an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

## Link(s)

Getting started with the EBD PostgreSQL Database Kubernetes Operator Part 1
- (https://ronekins.com/2021/12/17/getting-started-with-the-edb-postgresql-database-kubernetes-operator-and-portworx-storage/)

Getting started with the EBD PostgreSQL Database Kubernetes Operator Part 2
- (https://ronekins.com/2022/01/28/getting-started-with-the-edb-postgresql-database-kubernetes-operator-and-portworx-storage-part-2/)
