# Flask Deployment

Run the flask app by running this command

* For Windows CMD

    ```
    set FLASK_APP=main.py
    flask run
    ```

* For PowerShell

    ```PowerShell
    $env:FLASK_APP="main.py"
    flask run
    ```

* For Linux Terminal

    ```bash
    export FLASK_APP=main.py
    flask run
    ```

Run the flask app in docker container

```
docker build -t deploy-flask:latest .

docker run -p 5000:5000 deploy-flask:latest
```
