#traefik3
For traefik via docker-compose
acme.json should be created blank, and is propagated on ```docker-compose up -d```


```bash
traefik3
├── data
│   ├── config.yml
│   ├── logs
│   ├── secrets
│   │   ├── basicauthuserpass.secret
│   │   ├── cloudf_dns_api_token.secret
│   │   └── email.secret
│   └── traefik.yml
└── docker-compose.yml
```
