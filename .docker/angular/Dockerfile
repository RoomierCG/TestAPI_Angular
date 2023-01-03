FROM node:14

# Crea el directorio de trabajo y establece como directorio de trabajo
WORKDIR /app

# Copia los archivos package.json y package-lock.json al directorio de trabajo
COPY package*.json /app/

# Instala las dependencias de npm
RUN npm install

# Copia el resto de los archivos del proyecto al directorio de trabajo
COPY . /app/

# Establece el comando predeterminado para la imagen
CMD ["npm", "start"]


# Expone el puerto 4000
EXPOSE 4000