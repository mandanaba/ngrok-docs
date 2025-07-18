<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-18T10:11:50Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_302lN8fWGZDUgZBpvfVGLksQLCf",
        "uri": "https://api.ngrok.com/reserved_domains/rd_302lN8fWGZDUgZBpvfVGLksQLCf"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_302lNprKCksfz5MoW5THpkYFLli",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-07-18T10:11:50Z",
      "uri": "https://api.ngrok.com/endpoints/ep_302lNprKCksfz5MoW5THpkYFLli",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-18T10:11:48Z",
      "hostport": "73c8436eedcc.ngrok.paid:443",
      "id": "ep_302lNVYuL0kPkjH7OZpa8R6D1Tp",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_302lGwc4Km5wOpxwn4jKPnbFPs1",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://73c8436eedcc.ngrok.paid",
      "tunnel": {
        "id": "tn_302lNVYuL0kPkjH7OZpa8R6D1Tp",
        "uri": "https://api.ngrok.com/tunnels/tn_302lNVYuL0kPkjH7OZpa8R6D1Tp"
      },
      "tunnel_session": {
        "id": "ts_302lNUANd6YPPAURTYRp7dBR4Ko",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_302lNUANd6YPPAURTYRp7dBR4Ko"
      },
      "type": "ephemeral",
      "updated_at": "2025-07-18T10:11:48Z",
      "upstream_url": "http://localhost:80",
      "url": "https://73c8436eedcc.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-18T10:11:45Z",
      "edge": {
        "id": "edgtls_302lNBIQT2vqD3yMWizHCEicuKX",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_302lNBIQT2vqD3yMWizHCEicuKX"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_302lNC11h7U2E3Qn9DvPcJy6nvP",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-07-18T10:11:45Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
