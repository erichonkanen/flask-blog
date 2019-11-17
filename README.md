### Running

```
  pip install -r requirements.txt
  pip install -e .

  export FLASK_APP=landshare
  export FLASK_ENV=development

  flask init-db
  flask run

  # test marshmallow json resource.
  curl http://127.0.0.1:5000/json
```
