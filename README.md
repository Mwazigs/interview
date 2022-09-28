Deploy to htdocs create interview folder.

access link is http://localhost/interview/public/


my sql create DB named login system

table 

DROP TABLE IF EXISTS "login system"."user";
CREATE TABLE  "login system"."user" (
  "user_id" int(11) NOT NULL DEFAULT 0,
  "user_name" varchar(50) NOT NULL,
  "user_email" varchar(50) NOT NULL,
  "user_password" varchar(50) NOT NULL,
  "user_age" int(11) NOT NULL,
  "user_mobile" int(11) NOT NULL,
  PRIMARY KEY ("user_id")
) ENGINE=InnoDB DEFAULT CHARSET=latin1;

below to be inserted to DB.
1, 'denis', 'dnskombo@gmail.com', '1234', 34, 0721925143
