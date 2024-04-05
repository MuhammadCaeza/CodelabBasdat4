# CodelabBasdat4
CREATE TABLE MEMBERSHIP (

MEMBERSHIP_ID NUMBER PRIMARY KEY,

EMPLOYEE ID NUMBER,

MEMBER_STATUS VARCHAR(50),

CONSTRAINT FK_EMPLOYEE_ID FOREIGN KEY (EMPLOYEE_ID) REFERENCES EMPLOYEES (EMPLOYEE_ID) );

ALTER TABLE EMPLOYEES

ADD GENDER VARCHAR2(20);

insert into membership (membership id, employee id, member status) values (65618, 100, 'Continue')

select from membership

insert into countries (country id, country name, region id) values ('ID', 'Indonesia', 3)

insert into countries (country id, country name, region id) values ('MY', 'Malaysia', 3) insert into countries (country id, country name, region id) values ('TH', 'Thailand', 3)

select first name || '|| last name AS "Full Name", email, phone number as "NO HANDPHONE", salary as "GAJI" from employees
