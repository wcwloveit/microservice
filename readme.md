# ConfigServer Refresh
## Refresh All:
``
curl -X POST http://localhost:8888/bus/refresh
``
## Refresh Dedtination:
``
curl -X POST http://localhost:8888/bus/refresh?destination=web:**
``
## Refresh One:
``
curl -X POST http://localhost:8989/refresh
``