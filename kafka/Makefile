up:
	kubectl apply -f deployments/zookeeper.yml
	kubectl apply -f deployments/broker.yml
	kubectl apply -f services/zookeeper.yml
	kubectl apply -f services/broker.yml

down:
	kubectl delete -f deployments/zookeeper.yml
	kubectl delete -f deployments/broker.yml
	kubectl delete -f services/zookeeper.yml
	kubectl delete -f services/broker.yml
