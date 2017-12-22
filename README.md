# Webpacker with elm


```bash
rails new webpacker-elm -d postgresql -J -T --webpack=elm
bundle exec rails g controller pages index

<%= javascript_pack_tag 'hello_elm' %>

root to: 'pages#index'
```
