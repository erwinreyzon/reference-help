(best practice to git add . git commit -m "" git push origin REPO for every step)

1. create a new rails api app

rails new FILE-NAME-HERE

2. create controller

rails generate controller NAME-HERE

3. create model

rails generate model Example key1:string key2:string key3:integer key4:string

4. build a database add items in dbseed

(to wipe and make a new db)
rails db:drop db:create db:migrate db:seed

otherwise just
rails db:seed

5. modify routes and controller

get "/example", controller: "NAME OF CONTROLLER", action: "METHOD NAME"