创建过程：

```bash
$ bundle init
Writing new Gemfile to /Users/weli/works/sinatra-foo/Gemfile
````

```bash
$ bundle add sinatra
Fetching gem metadata from https://rubygems.org/....
Resolving dependencies...
...
Installing sinatra 2.0.8.1
$
```

```bash
$ cat Gemfile
# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# gem "rails"

gem "sinatra", "~> 2.0"
$
```
