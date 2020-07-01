# Get All Commission FN

## Development

- cp .env.example .env

- edit .env

```toml
GOOGLE_SERVICE_ACCOUNT_EMAIL=
GOOGLE_SPREADSHEET_ID_FROM_URL=
GOOGLE_PRIVATE_KEY=
```

- run `netlify dev` command

- test http://localhost:8888/api in postman

<details>
<summary>JSON PAYLOAD</summary>
 
```json
{
    "referral_code": "midascode"
}
```

</details>

## Deploy
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/thriftshop-fn/get-all-commission)

## Set Your Domain In Netlify

- Go to [Settings](https://app.netlify.com/sites/tss-test/settings/general)

- Click Change Site Name `${username}-tss-fn-get-all-commission.yourdomain.com`

## Production

- make post request with Needed *payload* to `${username}-tss-fn-get-all-commission.domain.com/api`


