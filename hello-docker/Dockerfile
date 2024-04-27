FROM node:21-alpine
# node nam je baza(runtime) a ovo 20-alpine je verzija koja se koristi (Linuxova neka)

WORKDIR /app
# /app je konvencija da bude WORKDIR

COPY . .
# Oznacava da kopiramo sve iz radnog direktorijuma u docker image
# prva tacka je trenutni direktorijum na nasoj masini a druga je path za trenutni direktorijum container-a

CMD node hello.js
# naglasavamo kako se pokrece nas projekat