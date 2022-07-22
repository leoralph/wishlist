
# Wishlist

Wishlist made with NextJS and Laravel, for sharing your wishlist between contacts.


## Stack

**Front-end:** NextJS, Zustand, Bootstrap

**Back-end:** PHP, Laravel, MySQL


## Locally Running

Clone project

```bash
  git clone https://github.com/leoralph/wishlist.git
```

Enter project directory

```bash
  cd wishlist
```

Enter API folder then install the dependencies

```bash
  cd api && composer install
```

Generate Laravel key

```base
    php artisan key:generate
```

Enter client folder then install the dependencies

```bash
  cd ../api && npm install
```

Run both servers, client and api
```bash
    cd api && php artisan serve
```
```bash
    cd client && npm run dev
```


## Authors

- [@leoralph](https://www.github.com/leoralph)


## Tags

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
