CREATE TABLE `weardrobe_management`.`cap` ( `cap_id` INT(11) NOT NULL , `size` CHAR(11) NOT NULL ) ENGINE = InnoDB;

INSERT INTO `cap` (`cap_id`, `size`) VALUES 
('1', 'S'),
('2','M'),
('3','L'),
('4','L'),
('5','M'),
('6','S');


CREATE TABLE `weardrobe_management`.`person` ( `person_id` INT(11) NOT NULL , `name` VARCHAR(11) NOT NULL ) ENGINE = InnoDB;

INSERT INTO `person` (`person_id`, `name`) VALUES
 ('1', 'abir'),
 ('2', 'rafi'),
 ('3', 'millat'),
 ('4', 'dhrubo'),
 ('5', 'millat'),
 ('6', 'turzo');




CREATE TABLE `weardrobe_management`.`t-shirt` ( `Tshirt_id` INT(11) NOT NULL , `size` CHAR(11) NOT NULL ) ENGINE = InnoDB;


INSERT INTO `t-shirt` (`Tshirt_id`, `size`) VALUES
 ('1', 'S'),
 ('2', 'M'),
 ('3', 'L'),
 ('4', 'XL'),
 ('5', 'S'),
 ('6', 'M'),
