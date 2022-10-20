Rename config_example.yml to config.yml and change credentials     

To get the theme Id
>     theme get --list -p=[password] -s="[shop_name].myshopify.com"

To download the theme
>     theme get -p=[password] -s="[shop_name].myshopify.com" --themeid=[theme_id]

To start theme watcher
>     theme watch