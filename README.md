#### Readme
This docker compose file is for main monitoring server. Ofc it need improvement on security side but, you can use it as a boiler plate.

You can run this by `docker compose up`
or 
To pull containers `docker compose create` and then start it via `docker compose start`


The folder structure might look like this

.
├── docker-compose.yml
├── loki
│   └── config-loki.yml
├── prometheus
│   └── prometheus.yml
└── README.md