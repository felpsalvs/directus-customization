**Docker repository for Directus and Customizable Extension**

This repository contains a docker file to run Directus, an open-source data management platform. It also contains a customizable extension that can be used to add new functionality to Directus.

**How ​​to use**

To use this repository, follow the steps below:

1. Clone the repository:

```
git clone https://github.com/bard/directus-docker-extensao-customizavel.git
```

2. Enter the repository directory:

```
cd directus-docker-extension-customizable
```

3. Build the docker image:

```
docker build -t directus-extension-customizable .
```

4. Run the docker image:

```
docker run -p 8080:8080 -d directus-extension-customizable
```

**Customizable Extension**

The customizable extension that comes with this repository adds a new functionality to Directus: the ability to create and manage users. To use this functionality, follow the steps below:

1. Access Directus in your browser.
2. Click on the "Settings" menu.
3. Click the "Extensions" tab.
4. Enable the "Users" extension.

After enabling the extension, you will be able to create and manage users in Directus. To create a new user, click the "New User" button. To manage an existing user, click the user's name.

**Settings**

The `docker-compose.yml` file contains the repository settings. You can modify these settings to suit your needs.

**Environment variables**

The repository uses the following environment variables:

* `DIRECTUS_HOST`: The Directus host.
* `DIRECTUS_PORT`: The Directus port.
* `DIRECTUS_DATABASE_HOST`: The Directus database host.
* `DIRECTUS_DATABASE_PORT`: The Directus database port.
* `DIRECTUS_DATABASE_NAME`: The name of the Directus database.
* `DIRECTUS_DATABASE_USERNAME`: The Directus database user name.
* `DIRECTUS_DATABASE_PASSWORD`: The Directus database user password.
* `EXTENSAO_CUSTOMIZAVEL_ENABLED`: Whether the customizable extension is enabled.

**Other information**

For more information about Directus, see the documentation: [https://docs.directus.io/](https://docs.directus.io/).

**Contributions**

Contributions are welcome. To contribute, submit a pull request.
