# Rocket_Elevators_Information_System
Application for website of the Company of Rocket Elevators
## URL
<https://tailleferjf.cf/>
## Gems used
* gem 'devise'


* gem 'rails-admin'


* gem 'faker'


* gem 'rubocop'
      https://github.com/rubocop-hq/rubocop
* gem 'sprockets-rails'
      https://github.com/rails/sprockets-rails/
* gem 'hirb'
      http://tagaholic.me/hirb/doc/index.html
      to use open -  
                  -open rails console in terminal
                  -run : Hirb.enable ( everytime you open the console)
* df
* df
* fd
* 

### pour la creation des tables dans mysql avec model
rails g model TableName
pour Quotes Employees Users

### pour les seeds

## Infos development:
### After pull:
```
bundle install
rails db:drop
rails db:create
rails db:migrate
rails db:seed ( if you want to populate your database )
```
📚 Instructions to acces to the admin panel:

To log as Admin:

```sh
1. Navigation bar : Member
2. Login
3. Username: mathieu.houde@codeboxx.biz
   password: 123456
4. Member : Admin Panel
```

## :memo: Routes

- homepage: <b>/</b>
- residential page: <b>/residential</b>
- commercial page: <b>/commercial</b>
- form page: <b>/form</b>
- thank you page: <b>/thank-you</b>
- Admin panel: <b>/admin</b>

```sh
rake routes
```
![](routes.png)

## Admin log-in instructions:
```
1. Sign up as a new user
2. CD in the project directory with your CLI
3. Type in `rails c`
4. Type in `@user = User.first`
5. Type in `@user.admin = true`
6. Type in `@user.save`
7. Go back to your localhost:3000
8. You should now have a Employees section link. You can also add /admin to the address. Will only work for admins.
```





















# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
# Rocket_Elevators_Information_System
