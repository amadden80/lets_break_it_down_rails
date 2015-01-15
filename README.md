Let's Break It Down!


[General Assembly](http://generalassemb.ly)



```bash

rails new sign_up_time -d postgresql -T
cd sign_up_time
bin/rake db:create
bin/rails generate scaffold User name:string email:string message:text color:string
bin/rake db:migrate
rails s

```
