
#### Example Request
```bash
curl \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"metadata":"{\"environment\": \"staging\"}","description":"ip policy creations","sources":[{"type":"ip_policy_created.v0"}],"destination_ids":["ed_2GjEzTJqqQrhMr5w3B4stWzrTmo"]}' \
https://api.ngrok.com/event_subscriptions