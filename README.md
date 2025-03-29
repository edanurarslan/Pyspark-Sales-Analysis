# TR:

# PySpark ile Büyük Veri Projesi

Bu proje, **Milli Teknoloji Akademisi** kapsamında gerçekleştirilen bir **İleri Veri İşleme Modül Projesi**dir.  
Projenin amacı, 2023 yılına ait jacket ürün satışlarını analiz ederek aşağıdaki konuları incelemektir:

- Jacket satışlarının bölgelere göre miktar ve ciro bazında analizi
- Her perakendecinin en yüksek ciro yaptığı bölgenin belirlenmesi
- Satış, müşteri ve tedarikçi davranışlarının veri ile değerlendirilmesi

Veriler **Parquet formatında** olup, analizler **Apache Spark (PySpark)** ile gerçekleştirilmiştir.

---

## 📊 Kullanılan Veri Tabloları

| Tablo Adı         | Açıklama                         |
|-------------------|----------------------------------|
| `FactSale`        | Satış işlemleri                  |
| `FactPurchase`    | Ürün satın alma işlemleri        |
| `DimCustomer`     | Müşteri bilgileri                |
| `DimRetailer`     | Perakendeci bilgileri            |
| `DimProduct`      | Ürün bilgileri                   |
| `DimRegion`       | Şehir ve bölge eşleşmeleri       |
| `DimDate`         | Tarih bilgileri (gün/ay/yıl)     |
| `DimSupplier`     | Tedarikçi bilgileri              |

---

## 🔍 Yapılan Analizler

- 2023 Haziran–Ağustos dönemine ait jacket satışlarının bölgesel performans analizi
- Perakendecilerin müşteri bazlı ciro dağılımı ve en güçlü olduğu bölgenin tespiti
- Sipariş yoğunluğu, ortalama sipariş değeri, tekrar eden müşteri davranışları gibi ek analizler

---

## ⚙️ Kullanılan Teknolojiler

- Apache Spark (PySpark)
- Spark SQL
- Google Colab
- Pandas (görselleştirme için)
- Parquet dosya yapısı

---

## 📝 Lisans

Bu proje eğitim amaçlıdır ve açık kaynaklıdır.

---

# ENG:

# Big Data Project with PySpark

This project was developed as part of the **Advanced Data Processing Module** under the **National Technology Academy**.  
Its goal is to analyze jacket product sales from the year 2023 with a focus on:

- Regional analysis of jacket sales by quantity and revenue
- Identifying the top-grossing region per retailer
- Understanding sales, customer behavior, and supplier-related insights

All data is stored in **Parquet format**, and analyses are carried out using **Apache Spark (PySpark)**.

---

## 📊 Data Tables Used

| Table Name        | Description                      |
|-------------------|----------------------------------|
| `FactSale`        | Sales transactions               |
| `FactPurchase`    | Product purchase records         |
| `DimCustomer`     | Customer information             |
| `DimRetailer`     | Retailer details                 |
| `DimProduct`      | Product catalog                  |
| `DimRegion`       | Region and city mapping          |
| `DimDate`         | Date dimension (day/month/year)  |
| `DimSupplier`     | Supplier information             |

---

## 🔍 Performed Analyses

- Regional performance analysis of jacket sales during June–August 2023
- Determining the region where each retailer generates the most revenue
- Additional insights including order volume, average order value, and repeat customer behavior

---

## ⚙️ Technologies Used

- Apache Spark (PySpark)
- Spark SQL
- Google Colab
- Pandas (for visualization)
- Parquet file format

---

## 📝 License

This project is open-source and developed for educational purposes.

