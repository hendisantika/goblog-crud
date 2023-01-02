# goblog-crud

### Things todo list

1. Clone this repository: `git clone https://github.com/hendisantika/goblog-crud`
2. Navigate to the folder: `cd goblog-crud`
3. Create Database goblog then create table

```shell
DROP TABLE IF EXISTS `employee`;
CREATE TABLE `employee` (
  `id` int(6) unsigned NOT NULL AUTO_INCREMENT,
  `name` varchar(30) NOT NULL,
  `city` varchar(30) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;
```

4. Run `go run main.go`
5. Open your favorite browser: http://localhost:8080 

