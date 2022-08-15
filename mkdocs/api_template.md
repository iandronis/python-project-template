## Endpoint Title

endpoint description (if any)

**GET/POST/PUT/DELETE**  
**URL:** `/my/endpoint/url/path/`

**URL params**

| name        | description | example        |
|:------------|:------------|:---------------|
| url_param_1 | some descr  | 'some example' |
| url_param_2 | some descr  | 'some example' |

**Query params**

| name          | type          | description | example        |
|:--------------|---------------|:------------|:---------------|
| query_param_1 | query_type_1  | some descr  | 'some example' |
| query_param_2 | query_param_2 | some descr  | 'some example' |

**Headers**

| name     | type           | description | example        |
|:---------|----------------|:------------|:---------------|
| header_1 | header_type_1  | some descr  | 'some example' |
| header_2 | header_param_2 | some descr  | 'some example' |

**Request payload**

| name        | type             | description |
|:------------|:-----------------|:------------|
| attribute_1 | attribute_type_1 | some descr  |
| attribute_2 | attribute_type_2 | some descr  |

??? quote "example"
    ```json
    {
        "attribute_1": "value_1",
        "attribute_2": "value_2"
    }
    ```

**Successful status:** 200 OK

Some description

| name        | type             | description |
|:------------|:-----------------|:------------|
| attribute_1 | attribute_type_1 | some descr  |
| attribute_2 | attribute_type_2 | some descr  |

??? success "example"
    ```json
    {
        "attribute_1": "value_1",
        "attribute_2": "value_2"
    }
    ```

**Failed status:** 400 BAD_REQUEST

- description why it failed reason_1
    
    ??? fail "example"
        ```json
        {
        "attribute_1": "value_1",
        "attribute_2": "value_2"
        }
        ```
