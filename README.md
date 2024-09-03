# KrakenD: templating and config merge

Prerequisites:
- docker
- a EE LICENSE

```shell
docker compose up
```

## Tree

```
├── config
│   ├── flexible_config.json
│   ├── LICENSE
│   ├── settings
│   │   ├── dev
│   │   │   └── endpoints
│   │   │       └── endpoints.yml <==== Endpoints
│   │   └── global.yml   <============= Global configuration
│   └── templates
│       ├── endpoints.tmpl
│       └── krakend.tmpl
├── docker-compose.yml
├── output
│   └── krakend.json
└── README.md
```
