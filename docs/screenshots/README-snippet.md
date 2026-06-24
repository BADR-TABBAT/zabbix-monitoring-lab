# GitHub assets ready to upload

## Recommended safe approach
- **Do not publish the full raw internship report publicly without checking it first**.
- Your report contains **real organization names, personal names, internal IP addresses, SNMP community values, and technical configuration details**.
- For GitHub, it is better to upload:
  1. a **sanitized (public) PDF version**
  2. selected screenshots in `docs/screenshots/`
  3. a short technical summary in `README.md`

## Suggested structure
```text
zabbix-monitoring-lab/
├── README.md
└── docs/
    ├── rapport-public.pdf
    └── screenshots/
        ├── ...png
```

## README snippet
```md
## Documentation
- [Public internship report](docs/rapport-public.pdf)

## Screenshots

### Page 19
![](docs/screenshots/page-19.png)

### Page 20
![](docs/screenshots/page-20.png)

### Page 23
![](docs/screenshots/page-23.png)

### Page 24
![](docs/screenshots/page-24.png)

### Page 26
![](docs/screenshots/page-26.png)

### Page 28
![](docs/screenshots/page-28.png)

### Page 31
![](docs/screenshots/page-31.png)

### Page 32
![](docs/screenshots/page-32.png)

```
