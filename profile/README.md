# KNVB

This is the official github page of the Koninklijke Nederlandse Voetbalbond (Dutch National Football Association)

In the future we will provide technical resources to connect our fans with their teams and data. For now, please follow us at one of the following sites:

* [Official website](https://www.knvb.nl)
* [Oranje fans channel](https://www.onsoranje.nl)
* [Voetbal.nl for amateur activities](https://www.voetbal.nl/inloggen)
* [KNVB Shop](https://www.knvbshop.nl/)
* [Ticket Shop](https://ticketing.knvb.nl)


## Data Platform
One of the first projects built at the KNVB using github was our new data platform, intended to enable the next generation of football insights for our players, coaches, and fans. We have oriented heavily around open source technologies and using a mix of proven and emerging solutions to create a platform which is robust, reliable, and scalable. The tools we're using:
* [Azure](https://azure.microsoft.com/en-us) is the platform of choice for long term data storage (the lake) as well as ad hoc computing resources
* [Snowflake](https://www.snowflake.com/en/) serves as our main data platform for storage, analytics, and data modelling
* [Dagster](https://dagster.io) is used for our data orchestration and dependency management across a wide variety of sources and targets
* [Meltano](https://meltano.com/) provides the common in/out framework we use for moving data between disparate systems (eg MySQL to snowflake)
* [OpenTofu](https://opentofu.org/) governs all of our infrastructure as code
* [dbt](https://www.getdbt.com/) handles all data modelling and transformations within our snowflake environment
* [Github codespaces](https://github.com/features/codespaces) allow us to give every analyst and engineer a robust, consistent, fully featured development environment
