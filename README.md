my charts

helm package ./charts/k6-operator/

helm repo index --url https://phucnguyen25392.github.io/devops-charts/ --merge index.yaml .

use --merge flag to add new charts to an existing index incrementally.yaml:
helm repo index --url https://github.com/phucnguyen25392/devops-charts.git --merge index.yaml .
