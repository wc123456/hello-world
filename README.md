select * from cpcmenu m
where exists (select * from cpcmenu m2 where m.menupid=m2.menupid and m2.menuid=3);
