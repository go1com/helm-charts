Install chart releaser (https://github.com/helm/chart-releaser)

Chart releaser upload (master branch)

    /usr/local/bin/cr upload --config cr-config.yaml

Chart releaser index (gh-pages branch)

    /usr/local/bin/cr index -i ./index.yaml --config cr-config.yaml --charts-repo https://github.com/go1com/helm-charts.git

