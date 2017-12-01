# hello-world
select * from cpcmenu m start with m.menuid=3 connect by prior m.menupid=m.menuid ;
