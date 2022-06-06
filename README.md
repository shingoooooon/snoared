# 🏂 Snoared

Find your snowboard gear anywhere anytime.
<br>

🏠Home
![Home](/app/assets/images/Snoared_home.png "Home")

🏂List
![List](/app/assets/images/Snoared_index.png "Index")

📝Booking
![Booking](/app/assets/images/Snoared_show.png "Show")

<br>
App home: https://snoard.herokuapp.com/


## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=your_own_cloudinary_url_key
```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 6](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping

## Acknowledgements


## Team Members
- [Edmund Oh](https://github.com/Edzandpieces)
- [Shunjiro Tatsyzuka](https://www.linkedin.com/in/syatsuzuka/)
- [James Reed](https://github.com/Jimreed91)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License

