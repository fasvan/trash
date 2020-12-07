FROM python:3.7.2

ADD requirements.txt / 
# "cashing"
RUN pip install -r requirements.txt
ADD . /

CMD [ "pytest", "test_integration_staging.py", "--alluredir=allure-results"]
