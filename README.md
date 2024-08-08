create table productos (
uuid varchar2(100) primary key,
nombre varchar2(20) not null, 
precio number(5,2) not null,
categoria varchar2(10) not null
)
