
NAME = proxy
CONTAINERS = nginx sidecar-nse proxy-nsc
PODS = proxy-nsc nginx-nse
CHECK = export ITERATIONS=10 && export BATCHES=2 && scripts/verify_proxy_nsc.sh

include $(TOP)/mk/targets.mk