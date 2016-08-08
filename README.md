## Table of Contents

* [Git](#git)
* [Rails](#rails)

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

* create a new rails app
```bash
# -T create without test framework
$ rails new my_project -T
```

* generate a new controller with actions
```bash
$ rails generate controller my_controller some_action another_action
```

* add new gems
```bash
$ bundle install
```

* display routes
```bash
$ rake routes
```