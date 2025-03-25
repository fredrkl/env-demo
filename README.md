# Env Demo

I strive to not use connection strings and secrets as much as possible. Instead I lean towards identity and access management technologies like federated identity and Azure Management Identity for example. Additionally, technologies like Azure App Configuration, can alleviate tedious repetitive configuration and secret management. However, there are times when I need to use a connection string or secret. Especially when setting up a local development environment. This is a demo of how to use a .env files and how to store them. Please use this as a last resort.

## What are .env files?

.env files are simple text files that contain key-value pairs. They are used to store configuration settings for your application. They are commonly used to store environment variables that your application needs to run. For example, you might have a .env file that contains the connection string to your database.

## Where do I store .env files?

You should never store .env files in your source code repository. This is because .env files often contain sensitive information like connection strings and secrets. Instead, you should store .env files in a secure location like Azure Key Vault or Azure App Configuration.
