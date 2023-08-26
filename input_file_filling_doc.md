<!--
# * * * * * * * * * * * * * * * * * * * * * * * * * * * * *
#  Title: Setup form generator                            *
#  Author: Shashank Shrivastav                            *
#  Email: contactshashank10@gmail.com                     *
#  Date: 2023                                             *
#  Code version: 2.0                                      *
#  Availability: https://github.com/GodOfPerceptionn      *
# * * * * * * * * * * * * * * * * * * * * * * * * * * * * *
-->

`This is documentation about fields present in input.json file`

> Note: If any data is not required in fields present in input.json make it empty. Don't remove the fields just make it empty like "token_url": "".

> Note: Custom authentication flow requires a manual change in the .clj file so go through the proper documentation.

> Note: Please go through all the documentation generated especially the .clj file once after generation.

> Note: For any query, error, or suggestions please contact to `contactshashank10@gmail.com`.

1. `api_name`: Enter the name of api you are working on.

2. `auth_option` : Enter the index of the authorization option supported by the source according to the documentation from the index of auth_option present at the top of the input.json file.

3. `base_url` : Enter the base URL from where the endpoint is being hit. Make sure to check the `/` at the end of the base URL and the beginning of the endpoint, It can't be present in both.

4. `Description` : Enter a small description about the source.

5. `doc_url` : Enter the document URL of the endpoint you are hitting in the temp entity.

6. `endpoint` : Enter the endpoint you are hitting. Make sure to check the `/` at the end of the base URL and the beginning of the endpoint, It can't be present in both.

7. `extract_path` : Enter the extract path of the primary key in the entity.

8. `header_params` : Enter/Add the key and value passed in the header parameter according to the documentation separated by space.

9. `primary_key` : Enter the primary key mentioned in the sample response of the entity.

10. `query_params` : Enter/Add the key and value passed in the query parameter according to documentation separated by space.

11. `refresh_url` : Enter the URL to fetch the `refresh token` in `OAuth` type authentication.

12. `Service` : Enter the index of service type the source is providing according to the documentation from the index of service_type present after auth_option in the input.json file.

13. `table_name` : Enter the table name of the entity.

14. `token_url` : Enter the URL to fetch the `access token` in  `OAuth` type authentication.

15. `URL` : Enter the URL of the main website homepage of the company, This is not the document link. It should start from `protocol` (HTTPS, HTTP) to `TLD`(.com, .in), it should not include any path or subdirectory.

16. `Subdomain` : Enter the Subdomain that is required in the base URL of the source according to the documentation.

17. `body_params` : Enter/Add the key and value passed in the body parameter according to documentation separated by space.

18. `body_params_foramt`: Enter the format in which the key and value are passed in body_params.

19. `graph_ql_body_params` : Enter the query that is passed in the body param of `graph QL` sources. Make sure to enter the query in raw format.