## VDP Helm Chart

[Helm](https://helm.sh) must be installed to use the charts. Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
helm repo add instill https://helm.instill.tech
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo vdp --devel` to see the chart.

To install the chart (alpha version):

```bash
helm install vdp instill/vdp --devel
```

To uninstall the chart:

```bash
helm uninstall vdp
```
