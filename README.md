# PHP5(mysqli)<>MySQL მაგალითი:
## SQL ბრძანების შეტანა ხდება ვარიაციით:
### $sql = "SQL კავშირის ბრძანება";
### $sql = "SELECT id FROM mytable ORDER BY id DESC LIMIT 1";
##### SQL ბრძანებები დაკავშირებულია SQL ბაზის სერვერის პროგრამასთან, პროგრამირების ენის საშუალებით ხდება მონაცემთა ბაზის პროგრამის ბრძანებითი კავშირის დამყარება.
#### P.s SQL ბრძანებების განხორციელება შეგიძლიათ პროგრამული ენის გამოყენების გარეშეც.
# SQL ცხრილის სვეტის ტიპები და მახასიათებლები:
## ტიპები
INT - რიცხვითი ფორმატი
VARCHAR - ჩვეულებრივი სიტყვათა მარაგისთვის (char გეცოდინებათ თუ იცით c/c++)
TEXT - ტექსტური მნიშვნელობისთვის (გამოიყენოთ პოსტის შესანახად)
DATE - დროის მნიშვნელობისთვის (შეინახავს როგორც: 9999-12-31)

## მახასიათებლები

Length/Values - გამოიყენება სიმბოლოთა მაქსიმალური ზომის მინიჭებისთვის, ან მსგავსი ტიპის ოპერაციის შესრულებისთვის

NULL - განულებული მნიშვნელობა

Default - მიენიჭოს მთავარი პრიორიტეტი, მაგალითად მიენიჭოს NULL განულებული მნიშვნელობა

Auto-Increment (A_I) - თავისით მოახდინოს მინიჭება, მაგალითად თუ გამოიყენებთ INT ტიპის ცვლადისთვის ყოველ ჯერზე გაზრდი +1_ით

## მოცემულია PHP5_ის საშუალებით Mysql_ზე მანიპულაციის მაგალითები. იხილეთ:

კავშირი - mysqli.connect.php

მონაცემთა ბაზის შექმნა - mysqli.create-db.php

ცხრილის შექმნა - mysqli.create-table.php

მონაცემთა ბაზის წაშლა - mysqli.drop-database.php

ცხრილის წაშლა -  mysqli.drop-table.php

ახალი ჩანაწერის შექმნა - mysqli.insert.php

ჩანაწერის გამოძახება - mysqli.select.php

ჩანაწერის რედაქტირება - mysqli.update.php

ჩანაწერის წაშლა - mysqli.delete.php

# ასევე იხილეთ ერთიანი მაგალითის ნიმუში /example დირექციაში
![A screenshot of the Arc theme](https://i.imgsafe.org/04/04b328ddd8.png)
