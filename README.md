# Tailwind CSS with Rails bug

## Installation

### Clone the repository

```shell
git clone git@github.com:thisisrishabh22/tailwind-rails-bug.git
cd tailwind-rails-bug
```

### Check your Ruby version

```shell
ruby -v
```

The ouput should start with something like `ruby 3.0.1`

If not,
<br/>
Install the right ruby version using [rbenv](https://github.com/rbenv/rbenv):

```shell
rbenv install 3.0.1
```

Install the right ruby version using [rvm](https://github.com/rvm/rvm):

```shell
rvm install 3.0.1
```

### Install the missing gems:

```shell
bundle install
```

### Initialize the database

```shell
rails db:create
rails db:migrate
```

## Serve

```shell
rails s
```
