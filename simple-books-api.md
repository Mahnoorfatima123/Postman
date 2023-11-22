# Simple Books API #

This API allows you to reserve a book.

The API is available at `https://simple-books-api.glitch.me`

## Endpoints ##

### Status ###

GET `/status`

Returns the status of the API.

### List of books ###

GET `/books`

Returns a list of books.

Optional query parameters:

- type: fiction or non-fiction
- limit: a number between 1 and 20.

### Get a single book ###

GET `/books/:bookId`

Retrieve detailed information about a book.

### Get all orders ###

GET `/orders`

Allows you to view all orders. Requires authentication.

### Get an order ###

GET `/orders/:orderId`

Allows you to view an existing order. Requires authentication.
```
### Possible Errors ###

Status code 409 - "API client already registered." Try changing the values for `clientEmail` and `clientName` to something else.
