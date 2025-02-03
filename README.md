# Number Classification API

This API classifies a given number and returns its mathematical properties along with a fun fact.

## Endpoint
`GET /api/classify-number?number=<number>`

## Example Request
`GET https://your-deployed-url/api/classify-number?number=371`

## Example Response
```json
{
  "number": 371,
  "is_prime": false,
  "is_perfect": false,
  "properties": ["armstrong", "odd"],
  "digit_sum": 11,
  "fun_fact": "371 is an Armstrong number since 3^3 + 7^3 + 1^3 = 371."
}

## This implementation meets all the requirements, including CORS handling, JSON responses, input validation, and deployment. Let me know if you need further assistance! 🚀
