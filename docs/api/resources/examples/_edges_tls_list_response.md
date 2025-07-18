<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-07-18T10:11:55Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_302lOM1A2HOtW63NF6KTqBLCZQI",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_302lOM1A2HOtW63NF6KTqBLCZQI"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_302lN5zUZ299rHHPGgtXkO9hJEU",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_302lN5zUZ299rHHPGgtXkO9hJEU"
        },
        "enabled": true
      },
      "created_at": "2025-07-18T10:11:45Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_302lNBIQT2vqD3yMWizHCEicuKX",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_302lNBIQT2vqD3yMWizHCEicuKX"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
