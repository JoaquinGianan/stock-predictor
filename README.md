# stock-predictor
 W13 - Build Container Image by JG

## Deliverables

- Link to the feature branch of your project repository
    - `Dockerfile`


W12 - stock-predictor by JG

curl -X 'POST' \
  'http://localhost:8000/predict' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "ticker": "GOOG",
  "days": 8
}'





 curl \
--header "Content-Type: application/json" \
--request POST \
--data '{"ticker":"MSFT", "days":7}' \
http://54.163.88.119:8000/predict
