# Pydantic

Pydantic is a  **data validation** , **settings management**and **parsing** library for Python, built around Python type hints. It allows you to define data models using standard Python types and automatically:

- **settings management** (loading and validating application configuration (like DATABASE_URL) from environment variables, .env files, or config files using structured models.)
-  **parsing** (converting input data (e.g., JSON, .env) into correct Python types like  Converting "age": "25" (string) to age: 25 (int))
- Validates data against the expected types  
- Converts and coerces data if necessary (e.g., strings to numbers)  
- Provides clear, structured error messages if validation fails  

---

## ✅ Key Features of Pydantic

- **Type-safe:** Uses Python's typing module (`str`, `int`, `List`, etc.)  
- **Automatic validation:** Automatic error messages when data doesn't match expected types  
- **Data conversion:** Conversion of input data into Python-native types such as `str`, `int`
- **Fast:** high performance
-  Seamless integration with FastAPI, langchain , SQLModel, ORMs, and more
-  Support for complex nested models, custom data types, and validators  

| Feature      | Description                                       |
| ------------ | ------------------------------------------------- |
| **Library**  | `pydantic`                                        |
| **Purpose**  | Data validation and parsing using type hints      |
| **Used in**  | FastAPI (request bodies, query parameters, responses i.e validate and parse request and response data.  ), LangChain (defining structured data models and validating inputs/outputs) |
| **Based on** | `BaseModel` classes                               |
| **Bonus**    | Autogenerates JSON schema (used in Swagger docs) |


---



