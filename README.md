# k8s-prometheus-grafana
Deploy Prometheus and Grafana to Kubernetes cluster with manifest files manually.

A readme file will be uploaded soon.

Change storage: "1Gi" in 24prometheus-statefulset.yaml.

Change host in 25prometheus-ingress.yaml

Change nginx.ingress.kubernetes.io/auth-secret and host in 25prometheus-ingress-basic-auth.yaml;

Change   admin-user and admin-password in 51grafana-secret.yaml.

Change server.domain, server.root_url, smtp.host, smtp.user, smtp.password, smtp.from_address, smtp.from_name 52grafana-configmap.yaml.

Change kube-slack/slack-channel, env.GF_DEFAULT_INSTANCE_NAME.value  in 54grafana-statefulset.yaml.

Change host in 55grafana-ingress.yaml.

Change host in 55grafana-ingress-basic-auth.yaml.