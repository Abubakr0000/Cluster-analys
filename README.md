# Cluster-analys

# Ma'lumotlarni klasterlash va klaster tahlili nima?

Ma'lumotlarni klasterlash deganda ma'lumotlarni ularning atributlari yoki xususiyatlariga ko'ra kichik klasterlarga guruhlash tushuniladi.
Klaster tahlili tibbiy tasvirlash, anomaliyalarni aniqlash miya va boshqalar kabi turli xil ilovalarda qo'llaniladi.

Klaster tahlili - bu nazoratsiz mashinani o'rganish algoritmining bir turi. U tegishli belgilarga ega bo'lmagan ma'lumotlar uchun ishlatiladi. 
Klasterlash bunday turdagi ma'lumotlar uchun qulaydir.
# Klasterlash algoritmlarining turlari
Quyida eng mashhur klasterlash algoritmlari keltirilgan:

1.Affinity Propagation

2.Hierarchical Agglomerative Clustering

3.BIRCH

4.DBSCAN

5.K-Means

6.Mini-Batch K-Means

7.Mean Shift

8.OPTICS

9.Spectral Clustering

10.Mixture of Gaussians

Ushbu maqolada biz ular orasida eng mashhur algoritmni ko'rib chiqamiz: K-Means Clustering.
#  K-means klasterlash algoritmi
Ushbu turdagi algoritmda ma'lumotlar ma'lumotlarni "K ajratilgan klasterlar" ga ajratadi yoki ajratadi.Ma'lumotlaringizga ko'ra klasterlar sonini (K) tanlashingiz kerak. Klaster markazlari yoki markazlar har bir klasterni ifodalaydi.

Algoritm qanday ishlaydi:

 1-qadam: Avvalo, klaster markazlarini yoki klasterlar sonini tanlang.
 2-qadam : Evklid masofasini hisoblab, har bir nuqtani eng yaqin klaster markaziga topshiring.
 3-qadam : Klaster markazlari ushbu klasterga tayinlangan nuqtalarning o'rtacha qiymatiga qarab optimallashtiriladi.
 4-qadam : Klaster markazlari ko'p harakat qilmayotganini yoki kichik masofani bosib o'tmasligini ko'rganimizdan so'ng, K-vositalari klasteri     birlashgan deb ishonch bilan aytishimiz mumkin.
Keling, Python-da K-means klasterlashni qanday amalga oshirishni ko'rib chiqaylik. Biz K-Means algoritmini amalga oshirish uchun mashhur Iris ma'lumotlar to'plamidan foydalandik.

<img width="737" alt="Снимок экрана 2022-10-06 в 14 42 51" src="https://user-images.githubusercontent.com/103623538/194281193-126149b7-4531-4ff7-bf95-ecfb85dcaea5.png">

# CSV faylini import qilamiz va dataframe yaratamiz.
<img width="669" alt="Снимок экрана 2022-10-06 в 14 44 29" src="https://user-images.githubusercontent.com/103623538/194282162-752caaaf-718c-4f2b-9630-791b5ff39d0b.png">

<img width="669" alt="Снимок экрана 2022-10-06 в 14 44 38" src="https://user-images.githubusercontent.com/103623538/194282279-89fb31af-8224-49f4-a422-30dea927677f.png">


<img width="605" alt="Снимок экрана 2022-10-06 в 14 44 52" src="https://user-images.githubusercontent.com/103623538/194282335-484a6988-7d1f-4827-a81f-938470dd1eec.png">


<img width="670" alt="Снимок экрана 2022-10-06 в 14 45 02" src="https://user-images.githubusercontent.com/103623538/194282613-1c938ead-0d85-47f1-a295-23ebfdffd2e4.png">


K Means klasterini yaratish vaqti keldi. Ishni osonlashtirish uchun biz matplotlib moduli yordamida syujet yaratamiz.

<img width="740" alt="Снимок экрана 2022-10-06 в 14 51 20" src="https://user-images.githubusercontent.com/103623538/194283083-08e21d02-7e28-45c0-9b0d-641e45fa8470.png">


<img width="407" alt="Снимок экрана 2022-10-06 в 14 51 46" src="https://user-images.githubusercontent.com/103623538/194283162-2f3c8917-ba4d-49ad-a31a-2b994b9a80ca.png">

K-means klasteri mustahkam algoritm bo'lsa-da, u mahalliy optimal minimumda yaqinlashmasligi mumkin.





