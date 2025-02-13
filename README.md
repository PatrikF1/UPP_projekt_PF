# EmailJS App

Ovo je aplikacija za slanje emailova koja je povezana s model-driven aplikacijom koristeći **Express.js**, **Axios** i **Camundu**. Automatizira slanje obavijesti direktno iz poslovnih procesa.

## Tehnologije
- **Node.js** (Express.js) – backend API
- **Axios** – HTTP zahtjevi prema EmailJS API-ju
- **Camunda** – BPMN modeliranje i postavljanje poslovnih procesa

## Postavljanje projekta

### Kloniranje repozitorija
```sh
 git clone <repo_link>
```

### Instalacija paketa
```sh
 npm install
```

### Kreiranje .env datoteke
Napravite `.env` datoteku u root folderu i dodajte:
```env
SERVICE_ID=your_service_id
TEMPLATE_ID=your_template_id
PUBLIC_KEY=your_public_key
PRIVATE_KEY=your_private_key
Sve se nalazi u EmailJs
```

### Pokretanje servera
```sh
 nodemon index.js
```

---

**Autor**: Patrik Fabijanić
