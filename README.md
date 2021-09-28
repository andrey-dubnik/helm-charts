# Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  `helm repo add temporalio https://temporalio.github.io/helm-charts`

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
temporalio` to see the charts.

To install the temporal chart:

  `helm install temporal temporalio/temporal`

To uninstall the chart:

  `helm delete temporal`
