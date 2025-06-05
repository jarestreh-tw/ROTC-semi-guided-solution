clean:
	kubectl delete ns crud-app
	kubectl delete pv postgres-data-persistent-volume

start:
	kubectl apply -f k8s -R

port-forward:
	kubectl port-forward -n crud-app services/backend-svc 8000:8000

delete-pods:
	kubectl delete po -n crud-app --all
