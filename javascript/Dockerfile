# Base image olarak Node.js kullanıyoruz
FROM node:18

# Çalışma dizinini ayarla
WORKDIR /app

# package.json dosyasını kopyala
COPY package.json .

# Bağımlılıkları kur
RUN npm install

# Uygulama dosyalarını kopyala
COPY . .

# Uygulamayı başlat
CMD ["node", "server.js"]