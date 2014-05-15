# API

Brief description of `user` end-point

## Uri

`{SERVER}/api/user[/id]`

### Available methods

`GET` / `POST` / `PUT`

- - -

### Examples

#### Get list

Returns a collection of user objects

[GET] `/api/user`

#### Response
```

	{
		[
			 {
				id: 1,
				name: Mickey Mouse,
				email: mickey@mouse.com
			},
			{
				id: ,
				name: Minnie Mouse,
				email: minnie@mouse.com
			},
		]
	}

```

#### Get a single user

Returns a user object

[GET] `/api/user/1`

#### Response
```

	{
		 {
			id: 1,
			name: Mickey Mouse,
			email: mickey@mouse.com
		}
	}

```



 - - -

## Object

```

	{

		user: {
			id: {int},
			name: {string},
			email: {string}
		}
	}

```