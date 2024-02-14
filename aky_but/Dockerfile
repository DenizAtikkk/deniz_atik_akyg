# Kullanılacak temel imaj
FROM python:3.8

# Çalışma dizini oluştur
WORKDIR /aky_but

# Gerekli dosyaları kopyala
COPY . /aky_but

# Gerekli Python kütüphanelerini yükle
RUN pip install openmeteo_requests requests_cache pandas retry_requests

# Uygulamayı çalıştır
CMD ["python", "but.py"]
