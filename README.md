## Development

// Adding default data to db 
```
mongo shop
db.pages.insertMany([
  {slug: '', meta_title: 'Home', enabled: true, is_system: true},
  {slug: 'checkout', meta_title: 'Checkout', enabled: true, is_system: true},
  {slug: 'checkout-success', meta_title: 'Thank You!', enabled: true, is_system: true},
  {slug: 'cart', meta_title: 'Cart', enabled: true, is_system: true},
  {slug: 'login', meta_title: 'Login', enabled: true, is_system: true},
  {slug: 'logout', meta_title: 'Logout', enabled: true, is_system: true},
  {slug: 'register', meta_title: 'Register', enabled: true, is_system: true},
  {slug: 'account', meta_title: 'Account', enabled: true, is_system: true}
]);
db.save;
```

// Running
```
npm i
npm run build
npm start
```

// Tested with node@10.3.0
