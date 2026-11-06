# SenEvent - Application DAWM

## En ligne

- Application web : https://senevent-chi.vercel.app
- Application Android (APK) :
https://expo.dev/accounts/alphamouhamadou01/projects/senevent/builds/638927fa-3da9-450a-bc96-fb697b47b2c5
- Version mobile : 1.0.0 (profil EAS "preview")
- Deploiement continu : chaque merge sur main met la production a jour, chaque Pull Request recoit une URL de previsualisation.

## Lancer le projet en local

- npm install a la racine
- Web : apps/web, creer .env.local (VITE_SUPABASE_URL, VITE_SUPABASE_ANON_KEY), npm run dev
- Mobile : apps/mobile, creer .env (EXPO_PUBLIC_...), npx expo start
