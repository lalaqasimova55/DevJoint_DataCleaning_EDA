#  Daşınmaz Əmlak Verilənlərinin Analizi

Bu layihədə Azərbaycan daşınmaz əmlak bazarına aid elanlar üzərində **Exploratory Data Analysis (EDA)** aparılmışdır. Layihənin əsas məqsədi verilənlər bazasını təmizləmək, məlumatların keyfiyyətini artırmaq, qiymətə təsir edən amilləri araşdırmaq və nəticələri müxtəlif vizuallaşdırmalar vasitəsilə təqdim etməkdir.

##  Layihənin məqsədi

Bu layihə çərçivəsində aşağıdakı işlər həyata keçirilmişdir:

- Verilənlər bazasının araşdırılması
- Çatışmayan dəyərlərin doldurulması
- Dublikat qeydlərin aşkarlanması və aradan qaldırılması
- Uyğunsuz və səhv məlumatların düzəldilməsi
- Əsas dəyişənlərin statistik analizi
- Qiymətə təsir edən amillərin araşdırılması
- Nəticələrin qrafiklər vasitəsilə vizuallaşdırılması


##  Verilənlərin hazırlanması

EDA mərhələsindən əvvəl aşağıdakı təmizləmə işləri aparılmışdır:

- Çatışmayan dəyərlər doldurulmuşdur.
- Dublikat qeydlər silinmişdir.
- Səhv daxil edilmiş sahə məlumatları (hektar və sot çevrilmələri) düzəldilmişdir.
- Təsvir hissəsinə əsasən uyğunsuz məlumatlar korrektə edilmişdir.
- Binary dəyişənlər ("var", "yoxdur") 0 və 1 formatına çevrilmişdir.
- m² qiyməti hesablanmış və yoxlanılmışdır.
- Outlier-lər müəyyən edilərək təhlil olunmuşdur.



##  Aparılan analizlər

Layihə çərçivəsində aşağıdakı analizlər aparılmışdır:

- Ədədi dəyişənlərin paylanması
- Outlier analizi
- Korrelyasiya analizi (Heatmap)
- Əmlak kateqoriyalarının müqayisəsi
- Kateqoriyalar üzrə orta qiymət analizi
- Kateqoriyalar üzrə elan sayı
- Sahə ilə qiymət arasındakı əlaqənin araşdırılması (Scatter Plot)


##  Əsas nəticələr

Analiz nəticəsində müəyyən edilmişdir ki:

- Əmlak qiymətləri sağa meylli paylanmaya malikdir.
- Sahə ilə ümumi qiymət arasında zəif müsbət əlaqə mövcuddur.
- Kommersiya təyinatlı obyektlərin orta qiyməti yaşayış tipli əmlaklardan daha yüksəkdir.
- Yeni tikili mənzillər elan bazasında ən çox paya malikdir.
- Əmlakın qiymətinə sahə ilə yanaşı məkan, kateqoriya və bina növü də təsir göstərir.
