phpRedisAdmin
=============

phpRedisAdmin�����ڹ���[Redis](http://redis.io/)���ݿ��һ���򵥽������.

��װ����
======================

ͨ��[composer](http://getcomposer.org/)��װ��ִ����������:

```
curl -s http://getcomposer.org/installer | php
php composer.phar create-project -s dev erik-dubbelboer/php-redis-admin path/to/install
```

You may also want to copy include/config.simple.inc.php to include/config.inc.php
and edit it with your specific redis configuration.

����ʹ�����·�ʽ��װ:

```
git clone https://github.com/huge-data/redis-ui.git
cd redis-ui/phpRedisAdmin
git clone https://github.com/nrk/predis.git vendor
```
��phpRedisAdmin�ŵ�ngxin�£�

```
sudo cp -r phpRedisAdmin /user/share/nginx/html/
sudo chown -R http:http phpRedisAdmin
```

����config.inc.php:

```
cd phpRedisAdmin/includes
sudo cp config.sample.inc.php config.inc.php
```

���������ļ��ο�ʾ���ļ�config.inc.php.example��


����
====

* ����֧�ֱ༭
* Javascriptʵ�ֱ�����
* ���õĴ��������
* ֧�ֲ�ͬ������֮���key�����ƶ�
* ֧��JSON��ʽ����
* �Զ���ָ�����������
