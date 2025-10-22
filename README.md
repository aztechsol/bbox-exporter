# bbox-exporter
Demo black box exporter example with alloy / grafana

`docker compose up`

| Service                                | URL                       |
|----------------------------------------|---------------------------|
| Blackbox exporter                      | `http://localhost:9115`   |
| Alloy prom scrape                      | `http://localhost:54321`  |
| Alloy using embedded blackbox exporter | `http://localhost:12345`  |
| Grafana UI                             | `http://localhost:3000`   |
| Mimir                                  | `http://localhost:9009`   |


Go to grafana-ui and open the dashboard
<img width="507" height="182" alt="image" src="https://github.com/user-attachments/assets/d5f5da01-689c-4b64-9319-acd5685cae4a" />

And you should see metrics for urls.
<img width="1890" height="808" alt="image" src="https://github.com/user-attachments/assets/44726c6a-7f72-45be-8181-4a655f5876d2" />
