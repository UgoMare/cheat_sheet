## Table of Contents

* [Git](#git)
* [Rails](#rails)
* [Rake](#rake)

## Git

* init
```bash
$ git init
```

* check remote
```bash
$ git remote -v
```

* add files
```bash
# add all in tree
$ git add .

# add a specific file
$ git add path/to/my/file
```

* commit changes
```bash
$ git commit -m 'my commit msg'
```

* push to remote
```bash
$ git push origin my_branch
```

## Rails

* run rails server
```bash
$ rails server
```

* run rails console
```bash
# --sandbox for running in sandbox mode
$ rails console
```

* create a new rails app
```bash
# -T create without test framework
$ rails new my_project -T
```

* generate a new controller with actions
```bash
$ rails generate controller my_controller some_action another_action
```

* destroy an already created controller
```bash
$ rails destroy controller my_controller some_action another_action
```

* generate a new model with attribues
```bash
$ rails generate model my_model some_attribute:some_type another_attribute:another_type
```

* generate a new migration
```bash
$ rails generate mogration MyMigrationDescription
```

* add new gems
```bash
$ bundle install
```

## Rake

* display routes
```bash
$ rake routes
```

* migrate the db
```bash
$ rake db:migrate
```

* rollback last migration
```bash
$ rake db:rollback
```

* populate the database with seed.rb
```bash
$ rake db:seed
```
