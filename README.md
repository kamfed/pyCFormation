CFormation
========

CLI that will generate Cloud Formation templates based on users input.

## Usage
Pass in resource components and descriptors for the resource to be created.

S3 Example w/ bucket name:

```
$ cformation --resource s3 --name TestName --region eu-west1 --properties ./prop.json --policies 
```

## Installation From Source

To install the package after you've cloned the repository, you'll want to run the following command from within the project directory:

```
$ pip install --user -e .
```

## Preparing for Development

Follow these steps to start developing with this project:

1. Ensure `pip` and `pipenv` are installed
2. Clone repository: `git clone git@github.com:example/pgbackup`
3. `cd` into the repository
4. Activate virtualenv: `pipenv shell`
5. Install dependencies: `pipenv install`
