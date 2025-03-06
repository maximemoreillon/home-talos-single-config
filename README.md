# Single node Talos cluster

```bash
talosctl gen config \
  --with-secrets secrets.yaml \
  --config-patch-control-plane @controlplane-patch.yml \
  --output-types controlplane \
  talos-single https://192.168.1.44:6443

```
