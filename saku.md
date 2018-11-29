# nginx
> show nginx stats

    pipenv run http GET :8080/stub_status
    pipenv run http GET :9113/metrics

# ping
> show apps stats

    pipenv run http GET :9001
    pipenv run http GET :9002
    pipenv run http GET :8082

# messages
> pipenv run http POST :8080/messages contents="hello world"

    pipenv run http GET :8080/messages

# id

    pipenv run http GET :8080/identity

# 404

    pipenv run http GET :8080/hoge

# ps

    docker ps

# jaeger

    open http://localhost:16686

# kibana

    open http://localhost:5601

# prom

    open http://localhost:9090
