# BahmniIndiaDistro Helm Charts Repository
## Usage
Helm must be installed to use the charts. Please refer to Helm's documentation to get started.

Once Helm has been set up correctly, add the repo as follows:

`helm repo add bahmniindia https://bahmniindiadistro.github.io/helm-charts`

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages.

You can then run helm search repo bahmni to see the latest stable charts. You can run `helm search repo bahmni -l --devel` to list all artifacts in the bahmniindia helm repo.
