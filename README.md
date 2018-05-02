# phpunittesting

Setup for PHP Unit test cases
Install php and phpunit on linux jenkins server
sudo yum install php56
wget https://phar.phpunit.de/phpunit-5.6.1.phar
php phpunit-5.6.1.phar — version
chmod +x phpunit-5.6.1.phar
sudo mv phpunit-5.6.1.phar /usr/local/bin/phpunit


How to run it

Run the below command and provide the path of all the test files. Currently it has . it means all files are present from where this command is running

/usr/local/bin/phpunit — log-junit test.xml -c phpunit.xml .
