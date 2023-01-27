# vy_gvisor

Related links

- https://katacontainers.io/
- https://github.com/kata-containers/kata-containers
- https://github.com/firecracker-microvm/firecracker
- https://firecracker-microvm.github.io/
- https://github.com/google/gvisor
- https://gvisor.dev/

Environment

```
$ kubectl version -o json
{
  "clientVersion": {
    "major": "1",
    "minor": "23",
    "gitVersion": "v1.23.4",
    "gitCommit": "e6c093d87ea4cbb530a7b2ae91e54c0842d8308a",
    "gitTreeState": "clean",
    "buildDate": "2022-02-16T12:38:05Z",
    "goVersion": "go1.17.7",
    "compiler": "gc",
    "platform": "linux/amd64"
  },
  "serverVersion": {
    "major": "1",
    "minor": "23",
    "gitVersion": "v1.23.4",
    "gitCommit": "e6c093d87ea4cbb530a7b2ae91e54c0842d8308a",
    "gitTreeState": "clean",
    "buildDate": "2022-02-16T12:32:02Z",
    "goVersion": "go1.17.7",
    "compiler": "gc",
    "platform": "linux/amd64"
  }
}
$ kubeadm version -o json
{
  "clientVersion": {
    "major": "1",
    "minor": "23",
    "gitVersion": "v1.23.4",
    "gitCommit": "e6c093d87ea4cbb530a7b2ae91e54c0842d8308a",
    "gitTreeState": "clean",
    "buildDate": "2022-02-16T12:36:57Z",
    "goVersion": "go1.17.7",
    "compiler": "gc",
    "platform": "linux/amd64"
  }
}
$ 
```
