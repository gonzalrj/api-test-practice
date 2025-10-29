# How to run the tests

## Via terminal run the ff:

export BASE_URL=http://localhost:8000
export API_KEY=secret-demo-key
pytest -v --alluredir allure-results

## To view allure report
allure serve allure-results          
