User Model
{
  "userId": "string",
  "age": 30,
  "gender": "female",
  "conditions": ["hypertension"],
  "lifestyle": {
    "sleep": 6,
    "activityLevel": "low"
  }
}
Health Record Model
{
  "recordId": "string",
  "type": "lab_report",
  "timestamp": "ISODate",
  "rawText": "string",
  "summary": "string",
  "embeddingId": "vector_id"
}
