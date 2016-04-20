# IFT232_1516S2A_University

CREATE TABLE `tbluniversity` (
  `stdId` int(11) NOT NULL AUTO_INCREMENT,
  `stdFirstName` varchar(50) NOT NULL,
  `stdLastName` varchar(50) NOT NULL,
  `stdGender` varchar(7) NOT NULL,
  `stdAcademicYear` tinyint(4) NOT NULL,
  `stdLebanese` bit(1) NOT NULL,
  `stdEmail` varchar(100) DEFAULT NULL,
  `stdAddress` varchar(200) DEFAULT NULL,
  PRIMARY KEY (`stdId`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;
