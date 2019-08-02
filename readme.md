# Laravel Homestead PHP5 / PHP56
* Forked from https://github.com/laravel/homestead

### Back to Homestead With PHP 5.6

This is meant to run along side of your normal Homestead box (which may be on php7 now), so `bash init.sh` creates a new homestead directory at ~/.homestead-56/ So setup this box's Homestead file at ~/.homestead-56/Homestead.yaml

I also highly recommend [Vagrant Manager](http://vagrantmanager.com) which helps keep track of which box is which!

For more information on how to setup homestead official documentation [it's located here](https://laravel.com/docs/5.4/homestead).

# Copy Sites From Original Homestead

```git clone https://github.com/codepotato/homestead-five-six.git ~/Homestead56```

```cd ~/Homestead56; cp -rv ~/.homestead/ ~/.homestead-56/; vagrant up```

## Or Setup Brand New Homestead56

 ```git clone https://github.com/codepotato/homestead-five-six.git ~/Homestead56```

```cd ~/Homestead56; bash init.sh; vagrant up```

## Mongo:
* Installing mongo? Run ```bash ~/Homestead56/other/install-mongo.sh```
