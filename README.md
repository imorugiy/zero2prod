# Migrate production database

`DATABASE_URL=${value} sqlx migrate run`

# Digital Ocean

Update spec:
`doctl apps list --format ID`
`doctl apps update d704ac6a-f499-4cba-a6d3-e5397138130a --spec spec.yaml`
