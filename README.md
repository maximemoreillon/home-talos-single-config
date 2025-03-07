# Single node Talos cluster

```bash
talosctl gen config \
  --with-secrets secrets.yaml \
  --config-patch-control-plane @controlplane-patch.yml \
  --output-types controlplane,talosconfig \
  talos-single https://192.168.1.57:6443

```
