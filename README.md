
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

# Cities API

Cities-API is a powerful and efficient open-source project written in Golang that provides a simple yet effective way to search for cities in a MySQL database. This project is useful for applications that need to query a large database of cities in real-time.

## API Reference

#### Search by city name

```text
  GET /city
```

| Parameter     | Type     | Description                        | Demo                                                                               |
| :------------ | :------- | :--------------------------------- | :--------------------------------------------------------------------------------- |
| `q` / `query` | `string` | **Required**. For example: Albuque | [/city?q=Albuque](https://cities-api.znanapraca.pl/city?q=Albuque)                 |
| `l` / `limit` | `string` | **Optional**. For example: 2       | [/city?q=Los+Ang&limit=2](https://cities-api.znanapraca.pl/city?q=Los+Ang&limit=2) |

### Example response

```json
[
 {
  "id": "111130",
  "name": "Albuquerque",
  "country_code": "US",
  "lat": 35.08449,
  "lng": -106.65114,
  "country": {
   "id": "233",
   "name": "United States",
   "iso2": "US",
   "phonecode": "1",
   "native": "United States",
   "emoji": "🇺🇸"
  },
  "state": {
   "id": "1423",
   "name": "New Mexico",
   "iso2": "NM"
  }
 }
]
```

More functions will be added Soon™.

## Data

- [Data Source](https://github.com/dr5hn/countries-states-cities-database)
- Database Dump is available in the cities_api.gz file.

## TODO

- [ ] Add more endpoints
- [ ] Add Installation instructions
- [ ] Add tests
- [x] Add demo link

## License

The Cities-API is open-sourced software licensed under the [MIT license](https://choosealicense.com/licenses/mit/).

PS. This is my first project in Golang, so please be kind. :)
