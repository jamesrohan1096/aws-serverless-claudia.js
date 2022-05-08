# AWS Serverless Applications using Claudia.js

# AWS services used:

- IAM
- Lambda
- API Gateway
- DynamoDB

`/pets`

```json
{
  "name": "Bosco",
  "species": "cat",
  "age": 19,
  "description": "Friendly black cat. Outdoor/indoor.",
  "weight": 13
}
```

## Schema

**pets**

- id: UUID (pk)
- petName: String
- species: String, 'cat' or 'dog'
- age: Number {years}
- description: String
- weight: Number (pounds)
