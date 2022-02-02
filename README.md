# The PADS
>select concat(Name,'(',SUBSTRING(Occupation, 1,1),')') from OCCUPATIONS order by Name asc;
select concat('There are a total of ',count(Occupation),' ',LOWER(Occupation),'s.') from OCCUPATIONS group by Occupation order by count(Occupation),Occupation desc ;
