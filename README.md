# E-commerce Back End
This application creates an API that accesses a mySQL database using the sequelize ORM in order to execute database operations based on models and relationships.
The API implements CRUD operations for categories, products and tags. This could be the coundation for an API that drives an e-commerce site.

## Description

This is the solution to the UC Berkeley Extensions coding boot camp module 12 challenge.
The challenge itself can be
found [here](https://bootcampspot.instructure.com/courses/3826/assignments/57127?module_item_id=1006828)
and [here](https://git.bootcampcontent.com/University-of-California---Berkeley/UCB-VIRT-FSF-PT-06-2023-U-LOLC/-/tree/main/13-ORM/02-Challenge).

## Table of Contents
- [Video](#video)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Video
You can view the video by clicking on the [link](https://drive.google.com/file/d/1eAEHNpFHcSI8RhG4FqmObQNNp_qSitQD/view?usp=sharing)

## Installation
A current version of node is required to run this application. Make sure you [download](https://nodejs.org/en/download) and install depending on your operating system.

## Usage
Start by cloning the following repo:
```bash
git clone git@github.com:srvidales/shopicity.git
```

CD into the directory:
```bash
cd shopicity
```

Then go ahead and install the dependencies and seed the database:
```bash
npm install
mysql -u root -p -e 'source ./db/schema.sql'
npm run seed
```

And finally run the application:
```bash
npm start
```

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Contributing
- [Sergio Vidales Perez](mailto://srvidales@gmail.com)
Starter Code:
[George](mailto://gcyoosf@gmail.com)
[Xander Rapstine](mailto://xanderrapstine@gmail.com)
[Xandromus](mailto://xanderrapstine@gmail.com)
[dependabot-bot](mailto://49699333+dependabot[bot]@users.noreply.github.com)
[georgeyoo](mailto://<gcyoosf@gmail.com>)
[rxtATX](mailto://rachel.thiim@gmail.com)

## Tests
Currently, this project does not include any tests.

## Questions
Feel free to reach out with additional questions here: [Contact Me](mailto://srvidales@gmail.com) or here [GitHub](https://github.com/srvidales).
