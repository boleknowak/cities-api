
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

# Cities API

Cities-API is a powerful and efficient open-source project written in Golang that provides a simple yet effective way to search for cities in a MySQL database. This project is useful for applications that need to query a large database of cities in real-time.

## API Reference

#### Search by city name

```http
  GET /city
```

| Parameter | Type     | Description                        |
| :-------- | :------- | :--------------------------------- |
| `q`       | `string` | **Required**. For example: Albuque |
| `limit`   | `string` | **Optional**. For example: 10      |

More functions will be added Soon™.

## Data

- [Data Source](https://github.com/dr5hn/countries-states-cities-database)
- Database Dump is available in the cities_api.gz file.

## License

The Cities-API is open-sourced software licensed under the [MIT license](https://choosealicense.com/licenses/mit/).
