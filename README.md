Flux reload configuration 

First update sources
`flux reconcile source git flux-system`

Then apply changes
`flux reconcile kustomization infrastructure`