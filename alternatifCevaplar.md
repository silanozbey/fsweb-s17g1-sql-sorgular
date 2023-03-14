









select * from  ogrenci where ograd in('Fidan','İsmail','Leyla')



select * from ogrenci where dtarih = 1989;






select * from ogrenci where dtarih=(select max(dtarih) from ogrenci );









<!-- SADECE ALTERNATİF CEVABI OLANLARI SORU NUMARASINA DENK GELECEK ŞEKİLDE EKLEDİM -->
 