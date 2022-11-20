# tugas5


SELECT username,id, email password FROM tbl_user; --menampilkan data

insert into tbl_user (email, password, username, address)
values ('didi@yahoo.com', 'poiuyt', '@didi', 'jalan rendang no.1000'); --insert data

delete from tbl_user where id=4; --delete data
select * from tbl_user; --menampilkan lagi data
UPDATE tbl_user SET username='abcdefg' where id=1; --update data

select * from tbl_user;
