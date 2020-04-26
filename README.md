# Confluent Open Source Helm Chart

The [Confluent Platform Helm charts](https://github.com/confluentinc/cp-helm-charts) enable you to deploy Confluent 
Platform services on Kubernetes for development, test, and proof of concept environments.

## Installing Charts

```
kubectl create ns kafka
helm package .
helm install --namespace kafka my-kafka ./cp-helm-charts-cn55-0.4.1.tgz
```

## Documentation

The Confluent Helm Chart documentation is located at 
[docs.confluent.io](https://docs.confluent.io/current/quickstart/cp-helm-charts/docs/index.html).

## Contributing

We welcome any contributions:

- Report all enhancements, bugs, and tasks as [GitHub issues](https://github.com/confluentinc/cp-helm-charts/issues)
- Provide fixes or enhancements by opening pull requests in GitHub

## Thanks

Huge thanks to:

- [Kafka helm chart](https://github.com/kubernetes/charts/tree/master/incubator/kafka)
- [ZooKeeper helm chart](https://github.com/kubernetes/charts/tree/master/incubator/zookeeper)
- [kubernetes-kafka](https://github.com/Yolean/kubernetes-kafka)
- [docker-kafka](https://github.com/solsson/dockerfiles)
