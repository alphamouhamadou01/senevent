# SenEvent - Application DAWM

## En ligne

- Application web : https://senevent-chi.vercel.app
- Application Android (APK) :
https://expo.dev/accounts/12alpha/projects/senevent/builds/c9960a7b-54c8-4350-a3d4-3072a971388d
- Version mobile : 1.0.0 (profil EAS "preview")
- Deploiement continu : chaque merge sur main met la production a jour, chaque Pull Request recoit une URL de previsualisation.

## Lancer le projet en local

- npm install a la racine
- Web : apps/web, creer .env.local (VITE_SUPABASE_URL, VITE_SUPABASE_ANON_KEY), npm run dev
- Mobile : apps/mobile, creer .env (EXPO_PUBLIC_...), npx expo start
