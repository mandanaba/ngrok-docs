<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_302lLBC290wSDNbkBwjadG3KMXu",
        "uri": "https://api.ngrok.com/tls_certificates/cert_302lLBC290wSDNbkBwjadG3KMXu"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.2yb53g7rqby7xdrr6.local-ngrok-cname.com",
      "created_at": "2025-07-18T10:11:29Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_302lLA6RcgUoxcxknAR8PWjVGuv",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_302lLA6RcgUoxcxknAR8PWjVGuv"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-07-18T10:11:29Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.2yb53g7rqby7xdrr6.local-ngrok-cname.com",
      "created_at": "2025-07-18T10:11:29Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_302lL5gL1U7WhvXfFE3ekzVF2WA",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_302lL5gL1U7WhvXfFE3ekzVF2WA"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-07-18T10:10:58Z",
      "description": "Your dev domain",
      "domain": "integral-genuinely-bat.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_302lHGQIKEKQCYl9d8lnMRHh1o2",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_302lHGQIKEKQCYl9d8lnMRHh1o2"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
