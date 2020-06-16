## Installing Charts from this Repository

Add the Repository to Helm:

    helm repo add helm-charts https://go1com.github.io/helm-charts

Install airflow:

    helm install helm-charts/airflow

## How to build chart

Package the chart

    helm package charts/<chart_name> --destination .deploy

Install chart releaser (https://github.com/helm/chart-releaser)

Chart releaser upload (master branch)

    /usr/local/bin/cr upload --config cr-config.yaml

Chart releaser index (gh-pages branch)

    /usr/local/bin/cr index -i ./index.yaml --config cr-config.yaml --charts-repo https://github.com/go1com/helm-charts.git

