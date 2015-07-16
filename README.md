# [Sequelize](https://github.com/sequelize/sequelize)-importer

> Import Sequelize models with ease.

## Setup

Create `index.js` inside your `models` folder.

```js
import Sequelize from 'sequelize';
import importer from '/Users/xpeper/Work/xpeper/nodejs/sequelize-importer'

let sequelize = new Sequelize('database', 'username', 'password');
let db = importer(sequelize, __dirname, {exclude: ['index.js']});

export default db;
```
