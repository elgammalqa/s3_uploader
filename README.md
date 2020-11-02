
### How to Run?

#### PreRequisites
  * [Python ~3.7](https://www.python.org/)
  
#### Setup Project:
#####  1. Clone or Download the project and `cd` into the `PyBucket/` folder.

#####  2. Upgrade pip
   ```
   $ python3 -m pip install --user --upgrade pip
   ```

#####  3. Install virtualenv
  - On macOS and Linux:
  ```
  $ python3 -m pip install --user virtualenv
  ```

  - On Windows:
  ```
  py -m pip install --user virtualenv
  ```
  
  
##### 4. Creating a virtual environment
 - On macOS and Linux:
 
 ```
 python3 -m venv env
 ```
 
 -On Windows:
 ```
 py -m venv env
 ```
#####  5. Commands to activate virtual env:

  - On macOS and Linux:
  ```
  $ source env/bin/activate
  ```

  - On Windows:
  ```
  .\env\Scripts\activate
  ```

#####  6. Install dependencies:
  ```
  $ pip install -r requirements.txt
  ```

#####  7. Change AWS *S3_KEY*, *S3_SECRET* and *S3_BUCKET* with your own values in `.env` file.
  ```
  source env/bin/actvate
  export FLASK_APP=app.py
  export FLASK_DEBUG=1

  export S3_BUCKET='YOUR_BUCKET_NAME' 
  export S3_KEY='YOUR_KEY' 
  export S3_SECRET='YOUR_SECRET_NOT_MINE' 
  ```

#### Launch Project
#####  1. run the app using command:
  ```
  $ flask run
  ```
  
#####  2. Access and test your application by visiting [http://localhost:5000](http://localhost:5000).


