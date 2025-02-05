# lambda_layer_python_jose
Lambda layer for use with upload handler lambda that provides Jose (JWT decode) package.

Package can be found at: https://pypi.org/project/python-jose/#history
Once the zipped package is created, create the AWS Lambda Layer with the following steps:
1. Navigate to Lambda in console
2. Navigate to 'Layers' on left side menu bar
3. Hit 'Create layer'
4. Name the layer & upload the .zip file
5. Attach layer to mediaviz serverless image upload package, and any others that require it.
