# Deploying Pipelines with Snowflake and dbt Labs

## About
This repository is a fork created from : https://github.com/Snowflake-Labs/sfguide-deploying-pipelines-with-snowflake-and-dbt-labs/tree/main

sniowflake guide : https://quickstarts.snowflake.com/guide/data_engineering_deploying_pipelines_with_snowflake_and_dbt_labs/index.html#8

## Dependencies :
`pip install dbt-snowflake==1.8.0`

## Notes:

1. The quickstart guide is to be followed, but please ensure to create dbt_hol_user in Snowflake, this can be found :
    `Dashboard > Admin > Users and Roles > Create user`
2. For the account param in the dbt_project.yml file use the account identifier value from Snowflake
3. DBT might prompt you to create a profile.yml file when issuing commands from cmd like dbt run or dbt seed
4. dbt has a cloud and core version, if you just use pip install dbt,  it will install dbt cloud by default, we need the dbt-snowflake to be installed
