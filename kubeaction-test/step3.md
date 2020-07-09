
# test simple flow

check flow
`cat simple-flow`{{excute}}

check flow
`kubectal apply -f simple-flow.yaml -n kubeaction`{{excute}}

check flow result
`kubectal get wfs`{{excute}}
