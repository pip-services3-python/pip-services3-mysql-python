# <img src="https://uploads-ssl.webflow.com/5ea5d3315186cf5ec60c3ee4/5edf1c94ce4c859f2b188094_logo.svg" alt="Pip.Services Logo" width="200"> <br/> MySQL components for Python Changelog

## <a name="3.1.0"></a> 3.1.0 (2021-05-14)

### Features
* Moved MySQLConnection to **connect** package
* Added type hints
* Fixed returned types for operations

## <a name="3.0.1"></a> 3.0.1 (2021-03-11)

### Bug fixes
* fixed MySqlPersistence.get_page_by_filter sort param
* fixed MySqlPersistence.get_list_by_filter return value

## <a name="3.0.0"></a> 3.0.0 (2021-02-25) 

Initial public release

### Features
* Added DefaultMySqlFactory
* Added MySqlConnectionResolver
* Added IdentifiableJsonMySqlPersistence
* Added IdentifiableMySqlPersistence
* Added MySqlConnection
* Added MySqlPersistence