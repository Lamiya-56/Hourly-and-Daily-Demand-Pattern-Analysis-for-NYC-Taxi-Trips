# 🚕 NYC Taxi Trip Analysis Project

Bu layihə New York City (NYC) taksi səfərlərinin **statistical analysis** və **visualization** prosesini əhatə edir.

## 📊 Dataset Overview
*   **Total Rows:** 1,458,644
*   **Total Columns:** 11
*   **Missing Values:** Yoxdur

## ⚙️ Data Processing & Feature Engineering
*   **Type Casting:** `pickup_datetime` və `dropoff_datetime` sütunları **datetime** formatına çevrildi.
*   **Feature Extraction:** Analiz üçün saat (`hour`), həftənin günü (`day_of_week`) və ay (`month`) sütunları yaradıldı.
*   **Unit Conversion:** `trip_duration` saniyədən dəqiqəyə çevrildi.
*   **Data Cleaning:** 24 saatdan uzun olan **outlier** (anomaliya) dəyərlər kənarlaşdırıldı.

## 📈 General Trends
NYC nəqliyyat ritmi həm biznes, həm də sosial həyatla sıx bağlıdır. Gün ərzində tələbat saat 05:00-dan başlayaraq kəskin artır və axşam saat 18:00 - 19:00 radələrində, yəni iş çıxışı zamanı öz zirvə nöqtəsinə çatır. Bunun əksinə olaraq, saat 04:00 - 05:00 aralığı şəhərin minimal hərəkətlilik dövrü hesab olunur.

## 🗓️ Weekly & Seasonal Dynamics
*   **Peak Day:** Cümə günü həftəlik aktivliyin ən yüksək olduğu gündür.
*   **Weekend Pattern:** Şənbə və Bazar günlərinin ilk saatlarında əyləncə həyatı ilə bağlı kəskin tələbat artımı müşahidə olunur.
*   **Seasonality:** Yanvar ayından etibarən başlayan artım trendi Mart-Aprel aylarında təxminən 10-12%-lik sıçrayışla nəticələnir.

## ⏱️ Trip Characteristics
İstifadəçilərin böyük əksəriyyəti 5-15 dəqiqəlik qısa məsafəli gedişlərə üstünlük verir. **Median** səfər müddəti 11.1 dəqiqə olduğu halda, **mean** (orta) dəyərin 15.9 dəqiqə olması tıxacların və uzunmüddətli nadir səfərlərin statistikaya birbaşa təsirini göstərir.

## 💡 Strategic Insights
Cümə axşamı və Cümə günlərinin axşam saatlarında yaranan sıxlıq zonaları (**high-density areas**) sürücü resurslarının və şəhər infrastrukturunun idarə olunması üçün əsas **target** nöqtələridir.
