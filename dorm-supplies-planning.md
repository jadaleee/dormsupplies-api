# Dorm Supplies Planning

### Basic Objects

##### User
```js
{
  id,
  email: String,
  hash: String,
  name: String,
  isAdmin: Bool,
  address: String,
  classYear: number,
  orders: [{
    items: [{
      itemId: String,
      quantity: Number,
      price: Number,
    }]
    purchasedDate: Date,
    deliveredDate: Date,
    isPaid: Boolean
  }]
}
```

##### Item
```js
{
  id,
  name: String,
  price: Number,
  description: String,
  quantity: Number,
  pic: String
  
}
```
