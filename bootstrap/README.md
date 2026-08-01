kubectl kustomize --enable-helm | kubectl apply --server-side --force-conflicts -f -
