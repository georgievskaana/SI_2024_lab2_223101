Ana Georgievska 223101
2. ![image](https://github.com/georgievskaana/SI_2024_lab2_223101/assets/138628647/821b91ae-bce3-49b4-8a79-9a317f96dc55)
3. Ciklomatskata kompleksnost na kodot, presmetana so metodot na broenje predikatni jazli, e 9+1=10.
4.Тест случаи според критериумот Every Branch
-allItems==nul Za da go pokrieme prviot exception
-allItems[null,"0123",301,0.1] , 0  So ova se pokriva if-ot za name==null, if-ot za validen barcode, if-ot za discount pogolem od 0, if-ot za item.getPrice() > 300 && item.getDiscount() > 0 && item.getBarcode().charAt(0) == '0' i if-ot sum <= payment koj vrakja true.
-allItems["name",null,200,0.1] , 0 Ovoj test case kje sluzi za da go pokrieme isklucokot za barcode ako e null.
-allItems["name","12a",200,0.1] , 0  Test primerov sluzi za da se pokrie frlanjeto na exepcion za nevaliden karakter vo barcode.
-allItems["name","123",200,0] , 0 Go pokrivame posledniot if (sum <= payment), else-ot kje vrati false.
5. 
