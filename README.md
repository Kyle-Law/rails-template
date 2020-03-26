# Rails Template

> Description 1

Description 2

![image1]()
<small><small><center>Image title</center></small></small>

## Built With

- Ruby
- Ruby on Rails
- RestClient Gem

## Project Structure

```
├── README.md
├── bin
│   └── main.rb
└── lib
    └── scraper.rb
    └── udacity_scraper.rb
    └── indeed_scraper.rb
    └── remoteio_scraper.rb
└── rspec
    └── scraper_spec.rb
    └── spec_helper.rb
```

## Video Presentation
Feel free to check out this [link](https://www.youtube.com/watch?v=BRg-9HNG4BI&feature=youtu.be) for a 3min video walkthrough :)

## Deployment
1) Git clone this repo and cd the to the `web_scraper` directory.
2) Run `bundle install` in command line to install Nokogiri and HTTParty Gem.
3) Run `bin/main.rb`.
4) Input either 'udacity', 'indeed', or 'remote.io' and follows the respective commands.
5) Tada! 'udacity_courses.csv', 'indeed_jobs.csv', or 'remote_io.csv' would be created at the root directory respectively :)

## Run tests
1) Git clone this repo and cd the to the `web_scraper` directory.
2) Install rspec with `gem install rspec`.
3) Run `rspec` in Command Line.
4) You would see failures because all 3 scraped files haven't been created yet.
5) To solve it, run `ruby bin/main.rb` and input 'udacity', 'indeed', and 'remote.io' for every execution.
6) Run `rspec` in CLI again. The test cases would success upon each file created :)

## Authors

👤 **Kyle Law**

- Github: [@Kyle-Law](https://github.com/Kyle-Law)
- Twitter: [@Kyle-Law](https://twitter.com/ZhunKhing)
- Linkedin: [Kyle law](https://www.linkedin.com/in/kyle-lawzhunkhing/)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/Kyle-Law/web_scraper/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Microverse
- Nokogiri gem
- HTTParty Parser
- Udacity.com
- Indeed.com
- Remote.io

## 📝 License

This project is [MIT](LICENSE) licensed.
