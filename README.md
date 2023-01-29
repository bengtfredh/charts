## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add fredhs-charts https://charts.fredhs.net

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  

You can then run `helm search repo fredhs-charts` to see the charts.

To install the \<example> chart:

    helm install my-<example> fredhs-charts/<example>

To uninstall the chart:

    helm delete my-<example>
