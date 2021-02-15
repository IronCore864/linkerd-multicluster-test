# Multicluster Manifests

Kustomize manifests to support the multicluster tutorials and demos. These are
laid out as follows:

- `base` - Take the
  [podinfo](https://github.com/stefanprodan/podinfo/tree/master/kustomize)
  manifest and add namespaces.
- `tiexin` - Modify the color and naming.
- `tiexin2` - Modify the color and naming.

`tiexin` and `tiexin2` are the name of the contexts for each cluster
