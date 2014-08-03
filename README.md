# Sample Chef Repo

```sh
  $ vi Gemfile
  $ bundle install --binstubs=bin --path=vendor/bundle
  $ bin/knife solo init .
  $ bin/berks install
  $ bin/kitchen init --driver=kitchen-docker
  $ bin/berks cookbook sample-erlang cookbooks/sample-erlang
```
