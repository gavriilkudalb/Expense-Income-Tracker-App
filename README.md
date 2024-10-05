![Logo](https://sun9-78.userapi.com/impg/UGE_i9QtOTz_GlL6JTh7O4MCsREkGdnGcUpZew/Q9xbo6TcBm0.jpg?size=32x32&quality=95&sign=2ec6c8870a1267c5b5ca6c21d8caf1bd&type=album)
# Expense Tracker

This Expense Tracker App is a user-friendly web application designed to help individuals manage their finances effectively. Users can easily track their income and expenses, categorize transactions, and visualize spending habits through interactive charts.


## Screenshots

![App Screenshot](https://sun9-15.userapi.com/impg/cf63tIHgXqcRqoRPfDjZRzHVU-Y1i8modsCFRw/1uegMODX9jg.jpg?size=1920x1080&quality=95&sign=08b15a669fead9e31c61cd88c2a46c80&type=album)

![App Screenshot](https://sun9-57.userapi.com/impg/uEAY7am8vMQlcaaBty0XSEOa8dkwJPVjjf6KCg/IVVruW_kKtY.jpg?size=1920x1080&quality=95&sign=12457b936ee4b18e53588ae589bb80b3&type=album)
## Features

- Setting your avatar
- Adding and edditing Expense/Income Categories


## API Reference is similar for Categories and Transactions

#### Get Categories/Transactions to Add or Edit

```http
  GET/AddOrEdit/Item
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `ItemId` | `int` | **Required**. Id of item to Add or Update |

#### Add/Update Category or Transaction

```http
  POST/AddOrEdit/Item
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `ItemId` | `int` | **Required**. Id of item to Add or Update |

#### Delete Category or Transaction

```http
  POST/Delete/Item
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `ItemId` | `int` | **Required**. Id of item to Add or Update |





## Tech Stack

**Client:** EJS, Razor

**Server:** .Net Core, C#


## Roadmap

- Registration/Login System

- Add Auto-Logo upploading

- Do the light/dark theme toggle

- Add several Languages

- Add more integrations
## Support

For support, text me in Telegram @vladmoneyprod\
Or email me gkudalb28@gmail.com
