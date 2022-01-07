# Help! Please Rescue Not-ready Nodes Immediately


<!--more-->

## About This Talk

For a Kubernetes cluster, nodes are crucial to make pods running properly. So it is indispensable to monitor nodes status and detect node problems. Node problem detector (NPD), an open source project in Kubernetes community, is a good answer to address this issue. Nowadays NPD has already been well accepted and widely used in production environments.

Actually identifying the problem is only the first step. What we need to do next is to handle those problems and rescue the nodes.

In this talk, we will list common problems and share how we establish rules to decide whether a node is ready or not and how to fix them if recoverable. Moreover, we will introduce some use scenarios on how we make a 99.9% uptime guarantee with ten thousand nodes in a single cluster. We will  share some experience on how to recover the nodes within 10 minutes as well.

## Full Talk

{{< youtube 7obeauqry_U >}}

---

You can also download and view [the PDF](https://static.sched.com/hosted_files/kccnceu20/3d/2020_KubeConEuro-Help-Please-Rescue-Not_Ready-Nodes-Immediately.pdf).

