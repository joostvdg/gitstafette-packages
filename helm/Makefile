# Install the server chart
install-server:
	helm upgrade --install gsf-server ./server --values server/example-values.yaml --namespace gsf-server --create-namespace

# Uninstall the server chart
uninstall-server:
	helm uninstall gsf-server --namespace gsf-server

# Debug a chart
template-server:
	helm template gsf-server ./server --values server/example-values.yaml --debug | yq
