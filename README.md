docker buildx build --platform linux/amd64 -t quay.io/mmortari/demo20231121-web:latest --push .

docker run -p 8080:8080 quay.io/mmortari/demo20231121-web

# When creating k8s route, ensure MODEL NAME consistent with the below:

http://demo.apps.mmortari.dev.datahub.redhat.com/v2/models/mnist-e2e/infer
