# WORK IN PROGRESS

# BirdNET-Go Helm Chart

This is a [Helm](https://helm.sh/) chart for deploying [BirdNET-Go](https://github.com/tphakala/birdnet-go)
to a [Kubernetes](https://kubernetes.io/) cluster.

### Add Helm repository

To install the repo just run:

```bash
helm repo add iszumpo https://iszumpo.github.io/birdnet-go-charts/
helm repo update
```

### Helm Charts

* [birdnet-go](https://iszumpo.github.io/birdnet-go-charts/)

  ```bash
  helm install your-release iszumpo/birdnet-go
  ```


### Configuration

#### Udev rules for mics

The chart uses [Akri](https://docs.akri.sh/) for attaching USB devices to the kubernetes pods. For more information about Akri and how to create the udev rules please read through my [article](https://medium.com/@hampusc/how-to-attach-usb-devices-to-kubernetes-pods-using-akri-19fb70d41f1e).
