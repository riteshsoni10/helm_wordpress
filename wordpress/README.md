```
cd wordpress # i.e in directory where Chart.yaml is kept
helm dep up
helm install wordpress -f values.yaml .
```