# native-cloud
A Framework To Create and Run own Native Clouds fully Kubernetes Compatible but is a Drop in Replacement

# Backend
The Main Backend is a Couchbase Database as this is Secure and Easy to Host and Scale for Kubernetes Compatibility we offer a
SyncGateway Adapter for etcd to write changes directly into a kubernetes Cluster without touching kubernetes it self.

# Concepts
EveryThing is a CRUD Service This Makes all Things Predictable. A Service is Transport indipendent.

## Examples


### Create a Single Node Cluster using docker on localhost
Cluster.json
```
cluster {
nodes: [{ machine-id: "Uniq", machine-description: "String" }],
id: "",
description: ""
}
```

nodeStateService
```
// Collects data from Cluster nodes and saves them as nodeState: entry
```

Static Persistent Deployment
```
```

thats it we have defined a Cluster


## Deploy gitlab on the cluster
- Get Cluster Information about nodes
- Chosse a Node run docker run on it and manage the traffic for the desired url and ssh tunnel?



## The Solution 
Deploy on OpenStack use kolla to deploy OpenStack it self via ansible

Once we Have OpenStack we can Deploy on That mesos, kubernetes, custom vms, we got network running and we got everything in place to Host a MultiUser Private or Public Cloud

## Your Company want to host a Website?
Deploy OpenStack 

## How to Deploy Auto Scaling LAMPP






















