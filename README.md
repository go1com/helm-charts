## How to build chart

Prerequisite: have the chart packaged (see https://github.com/go1com/helm-charts/blob/master/README.md#how-to-build-chart)

Generate chart releaser index (gh-pages branch only)

    /usr/local/bin/cr index -i ./index.yaml --config cr-config.yaml --charts-repo https://github.com/go1com/helm-charts.git

Commit the changes
