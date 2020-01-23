export TOKEN=$(curl -X POST http://localhost/keycloak/auth/realms/iot/protocol/openid-connect/token \
            -H 'Content-Type: application/x-www-form-urlencoded' \
            -d 'username=iotuser&password=iotuser&grant_type=password&client_id=gateway&client_secret=62c1ec01-1708-49f1-9633-a6a31105baf6' \
             | jq -r .access_token)