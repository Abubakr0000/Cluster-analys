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
 4-qadam : Klaster markazlari ko'p harakat qilmayotganini yoki kichik masofani bosib o'tmasligini ko'rganimizdan so'ng, K-vositalari klasteri birlashgan     deb ishonch bilan aytishimiz mumkin.
Keling, Python-da K-means klasterlashni qanday amalga oshirishni ko'rib chiqaylik. Biz K-Means algoritmini amalga oshirish uchun mashhur Iris ma'lumotlar to'plamidan foydalandik.

<img width="737" alt="Снимок экрана 2022-10-06 в 14 42 51" src="https://user-images.githubusercontent.com/103623538/194281193-126149b7-4531-4ff7-bf95-ecfb85dcaea5.png">





