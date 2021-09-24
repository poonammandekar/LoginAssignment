# LoginAssignment
to run app
1.set FLASK_APP=main.py
2.set FLASK_DEBUG=1
3.flask run

Mysql Table accounts
CREATE TABLE IF NOT EXISTS `accounts` (
    `id` int(11) NOT NULL AUTO_INCREMENT,
    `username` varchar(50) NOT NULL,
    `email` varchar(100) NOT NULL,
     `first_name` varchar(100) NOT NULL,
    `last_name` varchar(100) NOT NULL,
    `password` varchar(255) NOT NULL,
    `confirm_password` varchar(255) NOT NULL,
    PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;
