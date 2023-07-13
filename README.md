# Helm Chart EXAMPLE Project

  helm repo add onfire https://roxsrossgithub.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
mobagel` to see the charts.

To install the fastapi chart:

    helm install devfinder onfire/devfinder

To uninstall the chart:

    helm delete devfinder
