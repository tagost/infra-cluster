#jenkins

helm repo add jenkinsci https://charts.jenkins.io

helm repo update

infra-clusterhelm install jenkins -n jenkins -f jenkins-values.yaml jenkinsci/jenkins
