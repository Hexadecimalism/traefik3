#traefik3
For traefik via docker-compose
acme.json should be created blank probably with sudo, the chmod to 600. It is propagated on ```docker-compose up -d``` from within the traefik3 directory. docker-compose should have sudo or root access.


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
