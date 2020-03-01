# -*- mode: Python -*-
docker_build("garethr/snykin", ".")
k8s_yaml(helm("snykin", name="snykin"))
k8s_resource("snykin", port_forwards="3000:3000")
