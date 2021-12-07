### Welcome

This repository holds material for my corresponding youtube video on the topic.

In order to use it create the virtual environment, and install the dependencies.

``` bash
virtualenv pytesthml
.\pytesthtml\Scripts\activate
pip install pytest pytest-html
```

Now you can run the tests and generate the reports.

``` bash
pytest --html=report.html --self-contained-html
```
