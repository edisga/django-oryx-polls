

# Django and PostgreSQL sample for Azure App Service modified to run with Orxy image

The example here refers to the following github reference:
[Azure-Samples/djangoapp]
(https://github.com/Azure-Samples/djangoapp). 

This is a sample application that you can use to follow along with the tutorial at 
[Build a Python and PostgreSQL web app in Azure App Service](https://docs.microsoft.com/azure/app-service/containers/tutorial-python-postgresql-app). 

Run run this example correctly please follow the next requirements:

The database connection information is specified via environment variables `DBHOST`, `DBPASS`, `DBUSER`, and `DBNAME`. This app always uses the default PostgreSQL port. 

Update those settings in App Settings in the Azure Portal

Follow this article to build static files at 
[Django Tips with Oryx](https://github.com/Microsoft/Oryx/wiki/Django-Tips). 


# Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
