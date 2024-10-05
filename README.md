
![Logo]([https://sun9-72.userapi.com/s/v1/ig2/JxdzWEmuR4XoO1Kxz5BNvloAjyJ2mC2GuD2oA7qJcDhKKQLtnGnAoO2TBK3kqWLQ-nocwoTqhpk0CBOkai1RQ1iC.jpg?quality=95&as=32x32&from=bu&u=y77stU5HzjQnWw1RTFfNOb7DRfchcqtjqApCxC7QkLk&cs=32x32](https://sun9-45.userapi.com/impg/B96kSF2Yb0m2GvcOUGf9n4FezkfY7YGVinu1rg/2p4uRdF7DRM.jpg?size=32x32&quality=95&sign=bf739c373415f21ed6221f0682c8eb87&type=album))
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
